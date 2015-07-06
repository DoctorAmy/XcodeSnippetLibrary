#CB_XCode_Snippet_Library


##1.代码片段库 

* Xcode中代码片段,已文件加载的形式展示,也就是说,代码片段是一个文件


* 本库结构如下,只需将`CB_Code_Snippets_library`目录下的`所有文件`拷贝至Xcode代码片段文件夹中即可

	![image](https://github.com/ChaoBo/CB_XCode_Snippet_Library/blob/master/CB_Code_Snippets_Images/%E4%BB%A3%E7%A0%81%E7%89%87%E6%AE%B5%E5%BA%93%E7%BB%93%E6%9E%84.png?raw=true)


* 该代码片段库,对常用的代码片段进行了归类整理,目标只有一个,培养一个更`"懒惰"`的iOS程序猿


* 提高开发效率,`把你从重复的劳动中解脱出来`,以节省更多的时间,向iOS大牛进发!

    

##2.代码片段路径


* `~/Library/Developer/Xcode/UserData/CodeSnippets` 

   ![CodeSnippet Floder Path](https://github.com/ChaoBo/CB_XCode_Snippet_Library/blob/master/CB_Code_Snippets_Images/%E4%BB%A3%E7%A0%81%E7%89%87%E6%AE%B5%E6%9C%AC%E5%9C%B0%E8%B7%AF%E5%BE%84.png?raw=true)



##3.代码片段切换光标


* Tab键可以在代码中切换光标的位置


* 在代码中输入 `<#这是一个光标切换点#>` 即可生成一个光标切换点,如:

	![image](https://github.com/ChaoBo/CB_XCode_Snippet_Library/blob/master/CB_Code_Snippets_Images/%E5%85%89%E6%A0%87%E6%9C%AA%E9%80%89%E4%B8%AD.png?raw=true)



##4.代码片段的扩展名


* 代码片段扩展名 `.codesnippet`




##5.代码片段的命名


* 手动添加的代码片段,前面是一段又臭又长的标识,比如:

	![image](https://github.com/ChaoBo/CB_XCode_Snippet_Library/blob/master/CB_Code_Snippets_Images/%E9%BB%98%E8%AE%A4%E5%90%8D%E7%A7%B0.png?raw=true)


* 为了更好的适应人类阅读,本库中的代码片段全部摒弃该类标识,按照分类重新进行命名,比如:

	![image](https://github.com/ChaoBo/CB_XCode_Snippet_Library/blob/master/CB_Code_Snippets_Images/%E6%9B%B4%E6%94%B9%E5%90%8D%E7%A7%B0.png?raw=true)


* 该库中,每组分类名称头部一致,比如:

	![image](https://github.com/ChaoBo/CB_XCode_Snippet_Library/blob/master/CB_Code_Snippets_Images/%E4%BB%A3%E7%A0%81%E7%89%87%E6%AE%B5%E5%88%86%E7%B1%BB%E5%88%97%E8%A1%A8.png?raw=true)



##6.代码片段的标签


* 为了更好的展示代码片段库,建议已标签进行排序,每一组代码片段都有自己的标签


* `标签以2-5个字母为规范添加`,该组字母也就是这组代码片段的快捷键标识,比如:`属性*.codesnippet`的标签就是 `pt`

	![image](https://github.com/ChaoBo/CB_XCode_Snippet_Library/blob/master/CB_Code_Snippets_Images/%E4%BB%A3%E7%A0%81%E7%89%87%E6%AE%B5%E6%A0%87%E7%AD%BE.png?raw=true)




##7.代码片段快捷键


* 快捷键的分类同标签分类


* 快捷键前半部分在每组分类中均相同,比如添加属性的代码片段中,`ptstr`是添加一个`NSString` 的属性代码片段,`ptbtn`是添加一个`UIButton`的属性代码片段,都以`pt`开头,比如:

	![image](https://github.com/ChaoBo/CB_XCode_Snippet_Library/blob/master/CB_Code_Snippets_Images/%E5%BF%AB%E6%8D%B7%E9%94%AE.png?raw=true)




##8.代码片段文件展示格式


* Xcode代码片段库中的格式,前半部为代码前段的名称,后半部是代码片段的快捷键


* 你在XCode代码片段列表中可以看到如下标题,比如: `属性UILable - ptlab `," - "的`前半部分即就是该代码的名称(Name)`,`后半部分即就是代码片段的快捷键(ShortCut)`,以方便程序员查询,比如:

	![image](https://github.com/ChaoBo/CB_XCode_Snippet_Library/blob/master/CB_Code_Snippets_Images/%E4%BB%A3%E7%A0%81%E7%89%87%E6%AE%B5%E5%88%97%E8%A1%A8.png?raw=true)


* 所有的代码片段全局可见,即就是在代码中的任何地方输入代码片段的快捷键,均可调出该段代码,可见范围统一修改为`All`,比如:

	![image](https://github.com/ChaoBo/CB_XCode_Snippet_Library/blob/master/CB_Code_Snippets_Images/%E4%BB%A3%E7%A0%81%E7%89%87%E6%AE%B5%E7%9A%84%E5%8F%AF%E8%A7%81%E8%8C%83%E5%9B%B4.png?raw=true)



##9.代码片段提交注释格式

* 本库没有写任何Demo,为了更加明确使用方法,提交事格式固定.


* 每次提交注释的格式,每次提交按组分类,注释为`[前半部分]-[后半部分]`,前半部分为代码片段的分类,比如:`[属性添加]`,后半部分为代码片段快捷键的分组标识,比如:`[pt]`

	![image](https://github.com/ChaoBo/CB_XCode_Snippet_Library/blob/master/CB_Code_Snippets_Images/%E6%8F%90%E4%BA%A4%E6%A0%BC%E5%BC%8F.png?raw=true)
    
        













