# **GDSC University Of Yaounde 1 - Blog-Posts**

+-------------------------------+<br>
&ThinSpace;| &ThickSpace; Version: <kbd>[<img title="Française" alt="Française" src="https://th.bing.com/th/id/OIP.xryrkEIZjlg6rYj1BBT1LQAAAA?pid=ImgDet&rs=1" width="22">](./README.fr.md)</kbd>[*Français (Fr)*](./README.fr.md) &ThickSpace; |<br>
+-------------------------------+

This is a repository containing the social links of the community members of the Google Developer Student Clubs of the University Of Yaounde 1.

# 🎃 HacktoberFest 2023 🎃

![Hacktoberfest2023](https://external-preview.redd.it/hacktoberfest-2023-coming-soon-celebrating-ten-years-of-v0-7iAxY9XdcB1RlomtBWqvtgsafP-TAHZ3h0Goveo_Zjc.jpg?auto=webp&s=a7255699d6e0a0a1a7d2cdc5f10f35cf836861e5)

If you came here for Hacktoberfest, you're in the right place 🦇️:

Celebrate [Hacktoberfest](https://hacktoberfest.com/) by getting involved in the open source community by completing some tasks in this project.

## What is Hacktoberfest?

[HacktoberFest](https://hacktoberfest.com/) is digitalocean’s annual event that encourages people to contribute to open source throughout october. Much of modern tech infrastructure—including some of digitalocean’s own products—relies on open-source projects built and maintained by passionate people who often don’t have the staff or budgets to do much more than keep the project alive. HacktoberFest is all about giving back to those projects, sharpening skills, and celebrating all things open source, especially the people that make open source so special.

This repository is open to all members of the GitHub community. Any member may contribute to this project without being a collaborator.

## How can I contribute?

Contributions
There is 1 Task available and each task will be considered as valid by the Hacktoberfest team if properly carried out. Below is the task:

Prerequisite **Fork and Make the project available locally**. Run the command below for that:

    git clone https://github.com/<your-github-username>/blog-posts.git

- Create a branch

```markdown
git checkout -b myBlog main
```

- Make your changes. Create a file in the [**archives/2023**](./archives/2023/) directory. (filename = \<**your-github-username**\>.json>)
- List any tech blog posts (you can google any), as many as you want. It should respect the following formats:
  
### For a single blog post. 
Use this format if your want to submit a single blog post. [Example](./archives/2023/example-single.json)

```json
 {
    "Title": "Title of blog post",
    "Description": "A short description",
    "URL": "Link to blog post",
    "Author": "Author of the blog content"
  }
```
### For multiple blog posts. 
Use this format if your want to submit a multiple blog posts. [Example](./archives/2023/example-multiple.json)
```json
{
  "posts": [
    {
    "Title": "Title of blog post",
    "Description": "A short description",
    "URL": "Link to blog post",
    "Author": "Author of the blog content"
  },
    {
    "Title": "Setting up an apache server on Ubuntu",
    "Description": "A summarized process of installing an apache server",
    "Link": "https://onecode.hashnode.dev/setting-up-an-apache-server-on-ubuntu",
    "Author": "Ndi Lionel"
  }
   ]
}
```

## Committing
Please note the following before committing
1. Blog post links must be live and public.
2. All authors must be the real author(s) of the blog post.
3. All public domains are accepted.
4. Your pull request will be closed if you provide an invalid blog post author.
5. No editing on existing files on purpose. If you notice any problem with a file, please create an [Issue](https://github.com/gdscuy1/blog-posts/issues/new)

If everything is Ok, proceed with the following commands:
```markdown
git add .
git commit -m 'feat: added my blog post: <github-username>'
git push origin myBlog
```

- Create a new pull request from your forked repository (Click the `New Pull Request` tab located at the top of your repo). Make sure to compare across forks, then select this repository as target
- Add reviewers(optional)
- Wait for your pull request review and merge approval!

- **Please STAR this repository** if you had fun!

### Thanks to all our contributors

![contibutors](./CONTRIBUTORS.svg)

Made with :purple_heart: