Watermark functionality: Credit to: https://github.com/Webotvorba/ckfinder-plugin-imagewatermark-php
```
$config['ImageWatermark'] = [
    'imagePath' => __DIR__ . '/wm.png', // Path to watermark
    'position' => [
        'right'  => 'center',
        'bottom' => 'center'
    ],
    'minHeight' => 200
];

$config['Thumbnail'] = [
    'baseDir'     => dirname(__FILE__), // baseDir of ckfinder
    'thumbWidth'  => 150, // Width of thumb image
    'thumbHeight' => 150  // Height of thumb image
];```
