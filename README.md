

## 使用说明

	koaDebug.enable('*');


	var huyaDebug = koaDebug('faith_badge');
	huyaDebug('0进入index.js')



	var d = koaDebug('example:1');
	d({a:123});
	var d2 = koaDebug('example2:');
	d2('The color is %o', {b:456});


http://a.msstatic.com/huya/hd/cdn_libs/koa_debug.js

## 更详细的看这

[https://github.com/visionmedia/debug](https://github.com/visionmedia/debug)