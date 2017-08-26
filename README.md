jQuery.gMapping
===

Google マップ を表示させるjQueryプラグイン

### Installation ###
```
npm install --save jquery.gmapping
```

### Usage ###
```html
<script src="jquery.min.js"></script>
<script src="jquery.gmapping.min.js"></script>
<script>
  $(function() {
    $('#map').gMapping(lat, lng, options);
  });
</script>
```

### Options ###

- color.hue  
__Type__: string | number  
__Default__: ''  
マップの色相を設定

- color.saturation  
__Type__: number  
__Default__: 0  
マップの彩度を設定

- color.lightness  
__Type__: number  
__Default__: 0  
マップの輝度を設定

- marker.url  
__Type__: string  
__Default__: undefined  
マーカー画像のパス

- marker.size  
__Type__: [width: number, height: number]  
__Default__: undefined  
マーカーの大きさを設定

- marker.anchor  
__Type__: [x: number, y: number]  
__Default__: undefined  
マーカーの位置を調整

### jQuery Support ###
- 3.0.0+
- 2.0.0+
- 1.2.3+

### Browser Support ###
- Google Chrome  
- Safari  
- Firefox  
- Edge  
- IE 10+

### License ###  
MIT