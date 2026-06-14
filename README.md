##SFS-pack模组写入脚本
基于unitypy的SFS.pack写入脚本 主要用于汉化模组
①怎么使用
1.安装unitypy
2.cmd窗口运行
②所需文件〈与脚本处于同一目录〉
1.mod.pack
2.texts_to_translated_zh.json
③输出文件
mod_CN.pack
texts_to_translated_zh.json格式
"-9177355032084777435": {
    "Height": "高度",
    "Width": "宽度",
    "Angle": "角度",
    "X Size": "X尺寸",
    "Y Size": "Y尺寸",
    "Angle Smooth": "角度微调",
    "X Size Smooth": "X尺寸微调",
    "Y Size Smooth": "Y尺寸微调",
    "Width Smooth": "宽度微调",
    "Height Smooth": "高度微调",
    "Layer": "层级",
    "Depth": "深度"
}
##！！！！！必看！！！！！
目前v18存在提取文本过多的问题 请挨个核对翻译 否则会导致部件无法使用
浅存在写入问题 提取过少等问题
建议：浅和v18搭配使用 即v18写入 浅提取 若有漏的文字可以v18识别或者是手打(注意与游戏显示文本相同一个都不能少)
联系方式QQ2107478976
