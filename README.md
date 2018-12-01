# Biodiversity_Science_Style
Endnote Style for Biodiversity Science http://www.biodiversity-science.net/CN/column/column16.shtml

1. Import Reference Type 导入引用类型
- Edit - Preference - Reference Types - Import
- Choose [生物多样性 endnote reftype.xml](https://github.com/yf23/Biodiversity_Science_Style/blob/master/%E7%94%9F%E7%89%A9%E5%A4%9A%E6%A0%B7%E6%80%A7%20endnote%20reftype.xml)

2. Import Style 导入样式

 - Put [生物多样性 endnote style.ens](https://github.com/yf23/Biodiversity_Science_Style/blob/master/%E7%94%9F%E7%89%A9%E5%A4%9A%E6%A0%B7%E6%80%A7%20endnote%20style.ens) under Endnote style folder
 - Usually locates at C:\Users\\*<user_name>*\Documents\EndNote\Styles
 
3. Change In-text Chinese Citations 替换中文文献文中引用的英文部分
 - Use regex replacement in Word 替换 - 更多 - 使用通配符
 - Replace `([一-龥])( et al)` to `\1等`
 - Replace `([一-龥])( & )([一-龥])` to `\1和\3`
