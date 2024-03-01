# 工具库介绍

JavaScript 颜色转换和生成函数
该 JavaScript 库提供了一系列常用的颜色转换和生成函数。

randomColor(): 生成随机十六进制颜色值。
randomRGBColor(): 生成随机 RGB 颜色值。
rgbToHex(r, g, b): 将 RGB 颜色值转换为十六进制字符串。
hexToRgb(hex): 将十六进制颜色字符串转换为 RGB 颜色值。


var color = randomColor();
console.log("Random Color:", color);

var rgbColor = randomRGBColor();
console.log("Random RGB Color:", rgbColor);

var hex = rgbToHex(255, 0, 0);
console.log("RGB to Hex:", hex);

var rgb = hexToRgb("#FF0000");
console.log("Hex to RGB:", rgb);

