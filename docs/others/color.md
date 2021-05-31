# color

此站点支持自定义更换站点颜色主题，您可以根据自己的喜好搭配主题色彩

## 颜色主题

### 主色

> 默认 `Blue Grey`

点击色块可更换主题的主色

Red Pink Purple Deep Purple Indigo Blue Light Blue Cyan Teal Green Light Green Lime Yellow Amber Orange Deep Orange Brown Grey Blue Grey White

  
  var buttons = document.querySelectorAll\("button\[data-md-color-primary\]"\);  
  Array.prototype.forEach.call\(buttons, function\(button\) {  
    button.addEventListener\("click", function\(\) {  
      document.body.dataset.mdColorPrimary = this.dataset.mdColorPrimary;  
      localStorage.setItem\("data-md-color-primary",this.dataset.mdColorPrimary\);  
    }\)  
  }\)  


### 辅助色

> 默认 `Light Blue`

点击色块更换主题的辅助色

Red Pink Purple Deep Purple Indigo Blue Light Blue Cyan Teal Green Light Green Lime Yellow Amber Orange Deep Orange

  
  var buttons = document.querySelectorAll\("button\[data-md-color-accent\]"\);  
  Array.prototype.forEach.call\(buttons, function\(button\) {  
    button.addEventListener\("click", function\(\) {  
      document.body.dataset.mdColorAccent = this.dataset.mdColorAccent;  
      localStorage.setItem\("data-md-color-accent",this.dataset.mdColorAccent\);  
    }\)  
  }\)  


