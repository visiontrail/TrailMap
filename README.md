# What's TrailMap
Fork from https://github.com/wandergis/leaflet-echarts<br/>
一个可用于地理信息（点、线、区域）标记的开源框架，基于Echarts和leaflet制作


# 使用方法（Usage）

1. Confirm you have import `leaflet` first, <br/>
引入leaflet的js和css库自然不用说 
2. Import `eaflet-echarts.js` <br/>
可以通过npm安装，输入`npm install leaflet-echarts` 即可
3. Import `echarts.source.js` under directory `lib` <br/>
引入lib目录下的`echarts.source.js`文件
4. As you can use this plugin like this<br/>
按照下面的方法使用

	```
		var overlay = new L.echartsLayer(map, echarts);
    	var chartsContainer=overlay.getEchartsContainer();
    	var myChart=overlay.initECharts(chartsContainer);
		
		//这里跟百度echarts的map的option一样,the option is same as echarts map
    	var option={};
    	overlay.setOption(option);
   	 ```
5. If you don't konw how to use this plugin,hava a look at `/examples/index.html`<br/>
如果你不会用，看看examples目录下的`index.html` 


# 参考

>[https://github.com/ecomfe/echarts](https://github.com/ecomfe/echarts)
