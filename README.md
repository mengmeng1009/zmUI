# zmUI
猛哥的UI
# 写在前面的话
这个主要是为了方便猛哥自己来使用，不喜请路过，下载解压既可以使用
主要参考对象为Element
主要用于移动端
吐槽weui文档几乎等于无
吐槽mint-ui网站总是打不开
示例内的图标使用了Font Awesome 参考地址： http://fa5.dashgame.com

引用方式
`
   <script type="text/javascript" src="/js/jquery-3.3.1.min.js"></script>
   <link rel="stylesheet" href="/zmUI/FontAwesome/css/all.css"/>
   <link rel="stylesheet" href="/zmUI/css/zmui.css" />
   <script type="text/javascript" src="/zmUI/js/zmui.js"></script>
`
# 内容说明
1.  布局，上中下三部分布局整体内容，中间内容高度自动扩展【既如果没有其他一/二部分，会自动扩展高度】，内容超出之后，自动添加滚动条
     最外层zm-page采用flex布局，方便内部自动排版与扩展
     html示例代码
	 `
	 <div class="zm-page">
            <div class="zm-top">

            </div>
            <div class="zm-main">

            </div>
            <div class="zm-bottom">

            </div>
        </div>
	 `
2.  导航栏，不分底部,顶部，要能够平均分布，可以加图标，也可以不带图标
    zm-fenge作为分割线
     html示例代码
	 `
	 <div class="zm-daohang">
                    <div class="zm-item">
                        <span>纯文字</span>
                    </div>
                    <div class="zm-fenge">&nbsp;</div>
                    <div class="zm-item">
                        <div class="top-icon">
                            <i class="fas fa-universal-access"></i>
                            <span>带图标</span>
                        </div>
                    </div>
                    <div class="zm-fenge">&nbsp;</div>
                    <div class="zm-item">
                        <div class="left-icon">
                            <i class="fas fa-universal-access"></i>
                            <span>带图标</span>
                        </div>
                    </div>
                    <div class="zm-fenge">&nbsp;</div>
                    <div class="zm-item">
                        <i class="fas fa-universal-access"></i>
                    </div>
                </div>

	 `
3.  对话框里的消息气泡
     html示例代码
	 `
	 <div class="duihua" >
                        <div class="xiaoxi"  ><span>这是一条消息</span></div>
                    </div>
	 `

3.  遮罩层
     html示例代码
	 `
	 <div class="zm-zhezhao">
	 <!-- 自定义内容 -->
	 </div>
	 `
