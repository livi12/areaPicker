# areaPicker
省市区 三级联动

###调用说明
		$("body").areaPick({
		        selectId : {
		            province : "province1",     //不传默认查找id为 province的元素，必须传id
		            city     : "city1" ,        //同上，默认查找id为  city的元素
		            area     : "area1"          //默认查找id为area的元素
		        },
		        defaultArea : {
		            province : "浙江省" ,
		            city     : "杭州市" ,
		            area     : "西湖区"
		        }
		    });
    
###实现说明：
  该方法利用json格式把省市区逐步分解
