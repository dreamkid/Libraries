身份证识别

实现原理 通过拍照或者周期性从预览中获取某一帧图片解析获取身份证信息 <br>
核心代码 OcrEngine ocrEngine = new OcrEngine(); <br>
IDCard idCard = ocrEngine.recognize(MainActivity.this, 2, cropStream.toByteArray(), null);<br>