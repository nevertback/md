1. 来路统计，需要在后台增加对应区域的统计条目。
2. 传递格式：
安卓：  
iOS:  https://a.gamersky.com/app/之前统计路径/refer/点击区域的统计Id  
(/referer/ --> /refer/ 2018.02.26 更新)
安卓：  
* 首页  
intent://home?referer=点击区域的统计Id#Intent;scheme=gamersky;action=android.intent.action.VIEW;S.browser_fallback_url=http%3A%2F%2Fa.gamersky.com%2F;end  
uc qq浏览器  
gamersky://home?referer=点击区域的统计Id  


* 新闻详情页  
intent://home?action=news&id=934547&referer=点击区域的统计Id#Intent;scheme=gamersky;action=android.intent.action.VIEW;S.browser_fallback_url=http%3A%2F%2Fa.gamersky.com%2F;end  
uc qq浏览器  
gamersky://home?action=news&id=934547&referer=点击区域的统计Id  


* 打开首页游戏  
intent://home?tab=game&referer=点击区域的统计Id#Intent;scheme=gamersky;action=android.intent.action.VIEW;S.browser_fallback_url=http%3A%2F%2Fa.gamersky.com%2F;end  
uc qq浏览器  
gamersky://home?tab=game&referer=点击区域的统计Id  


* 打开游戏详情  
intent://home?id=862094&action=game&tab=game&referer=点击区域的统计Id#Intent;scheme=gamersky;action=android.intent.action.VIEW;S.browser_fallback_url=http%3A%2F%2Fa.gamersky.com%2F;end  
uc qq浏览器  
gamersky://home?id=862094&action=game&tab=game&referer=点击区域的统计Id  


* 打开游戏攻略集  
intent://home?action=game&id=862094&open=strategy&tab=game&referer=点击区域的统计Id#Intent;scheme=gamersky;action=android.intent.action.VIEW;S.browser_fallback_url=http%3A%2F%2Fa.gamersky.com%2F;end  
uc qq浏览器  
gamersky://home?action=game&id=862094&open=strategy&tab=game&referer=点击区域的统计Id  