# yqfkReport
使用 `GitHub Actions` 自动提交疫情防控通
> 由于校园网限制 填报时间改为7:11 AM (UTC时间 23:11)（再次拖后一个小时）
>
> 由于Github将限制`90天`不活跃仓库的Actions,尝试每次Push一个KeepAlive文件到仓库来保持活跃.
# How to Use
1. Fork 本仓库(需要GitHub账号)
2. 进入自己Fork的项目,选择 `Actions` 选项卡, Enable 项目.
![image.png](https://i.loli.net/2021/03/23/FyRLgVT8b9Gan5A.png)
3. 设置机密信息 (数字石大用户名密码) 选择 `Settings` -> `Secrets`
![image.png](https://i.loli.net/2021/03/23/dCwh2HQZclasYrU.png)
4. Star 项目,在 `Actions`-> `Report` -> build 处查看 输出
![image.png](https://i.loli.net/2021/03/23/M7OgRsk3iPCuTFc.png)

当输出中出现 `今日已经填报了` 即登录成功.
# Notification
设置在提交出现错误时会发送邮件到`Github`绑定的`Primary Email`地址,依赖于`Github Actions`报错功能,你可以在 `Settings->Notifications`中关闭报错功能.

![image](https://user-images.githubusercontent.com/44310445/138683790-334109cd-49f7-4d12-941f-0130bc99761b.png)

> *注意* 请勿过度依赖本项目 本项目的功能随时可能因为校园网或其他原因失败.
