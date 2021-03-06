# BearyChat Stash 手动配置指南

## 下载并安装 Stash2BearyChat 插件

对于 stash 3 的用户，请在 [stash2bearychat@1.3](https://github.com/bearyinnovative/stash2bearychat/releases/tag/1.3) 下载 jar 文件。

对于 bitbucket server 用户，请在 [stash2bearychat@2.0.0](https://github.com/bearyinnovative/stash2bearychat/releases/tag/2.0.0) 下载 jar 文件。

## 安装插件

进入网址 http://{your-stash-site}/admin 里面的 ADD-ONS 中的 Manage add-ons 页面如下图

![](/tutorials/image/stash_manage_add_ons.png)

点击「Upload add-on」选项

![](/tutorials/image/stash_upload_add_ons.png)

点击选择文件，选择刚刚下载的插件 jar 文件。选择 Upload 上传

![](/tutorials/image/stash_uploading_add_ons.png)

## 设置 Stash2BearyChat 插件

插件安装完成之后，回到你想设置的仓库，然后点击左侧的「Settings」。

![](/tutorials/image/stash_repo_setting.png)

进入后找到「ADD_ONS」下的「BearyChat settings」选上你想要推送的类型，现在只支持 pull request 和 push 事件，之后再填写上你的 BearyChat Stash 机器人的 webhook url。点击Save保存。

保存后会刷新页面，刷新后似乎都没有变，但是实际上已经保存了，可以通过发一个 pull request 或者 push 来查看效果。下图就是 pull request 重新打开的事件消息。

![](/tutorials/image/stash_pull_request_msg.png)
