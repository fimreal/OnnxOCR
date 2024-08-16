github 限制 25M 大小，需要手动合并模型文件（原仓库使用百度云盘下载实在是太慢了）
 
```bash
  cat rec.onnx.split_0* >rec.onnx.new
  md5sum -c rec.onnx.md5sum
```
