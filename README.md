# Flutter_doc_CokBK_IMG_Display_images_from_the_internet
 Flutter_doc_CokBK_IMG_Display_images_from_the_internet
Display images from the internet
================================

1.  [Cookbook](https://docs.flutter.dev/cookbook)
2.  [Images](https://docs.flutter.dev/cookbook/images)
3.  [Display images from the internet](https://docs.flutter.dev/cookbook/images/network-image)

Displaying images is fundamental for most mobile apps. Flutter provides the [`Image`](https://api.flutter.dev/flutter/widgets/Image-class.html) widget to display different types of images.

To work with images from a URL, use the [`Image.network()`](https://api.flutter.dev/flutter/widgets/Image/Image.network.html) constructor.

content_copy

```
Image.network('https://picsum.photos/250?image=9'),
```

[](https://docs.flutter.dev/cookbook/images/network-image#bonus-animated-gifs)Bonus: animated gifs
--------------------------------------------------------------------------------------------------

One useful thing about the `Image` widget: It supports animated gifs.

content_copy

```
Image.network(
    'https://docs.flutter.dev/assets/images/dash/dash-fainting.gif');
```

`\
`
