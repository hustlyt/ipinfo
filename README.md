# ipinfo
php版获取本机IP信息 powerd by Cloudflare


地址：https://hostloc.com/thread-1170806-1-1.html


借助Cloudflare弄的，可以查询ip的一些基础信息。  
注：cloudflare规则由我完成，php代码由ChatGPT完成。代码地址 https://github.com/ytree001/ipinfo  
要配合以下Cloudflare规则使用。方法二的规则自行研究。  
Rules-Transform Rules-Modify Request Header  
见图
![image](https://github.com/hustlyt/ipinfo/assets/36230752/98e5eaa6-52b0-4465-afdd-c758f7312f7c)

使用方法：
1.直接访问 https://ip.seek.gq
![image](https://github.com/hustlyt/ipinfo/assets/36230752/71391ee2-4192-4030-b067-025ad3588994)


2.从响应头里获取
![image](https://github.com/hustlyt/ipinfo/assets/36230752/667b6c69-eb1f-422a-a2aa-ddd3b79cf61f)
