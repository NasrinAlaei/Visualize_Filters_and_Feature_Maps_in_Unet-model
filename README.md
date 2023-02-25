# Visualize_Filters_and_Feature_Maps_in_Unet-model


در این آموزش، نحوه ایجاد تصویر ساده برای فیلترها و نقشه های ویژگی در یک شبکه عصبی کانولوشن را خواهید یافت. بدین منظور از مدل Unet استفاده شده است.

مدل Unet یک شبکه عصبی کاملا کانولوشنال ساده که برای تقسیم بندی باینری یعنی طبقه بندی پیکسلی پیش زمینه و پس زمینه استفاده می شود.
این  مدل شامل 45 لایه convolution و 7 لایه pooling میباشد که تصویر ساده از فیلترهای این نوع لایه ها آورده شده است.
در ابتدا یک تصویرسازی برای فیلترهای خاص در یک شبکه عصبی کانولوشن میبینید و سپس نحوه ایجاد تحلیل بصری برای نقشه های ویژگی خاص در یک شبکه عصبی کانولوشن.


اجرای این مثال برای لایه های pooling منجر به هفت نمودار می شود که نقشه های ویژگی را از هفت بلاک اصلی مدل نشان می دهد.

می‌توانیم ببینیم که نقشه‌های ویژگی نزدیک‌تر به ورودی مدل، جزئیات بسیار دقیقی را در تصویر ثبت می‌کنند و با پیشروی عمیق‌تر در مدل، نقشه‌های ویژگی جزئیات کمتر و کمتری را نشان می‌دهند، زیرا این مدل ویژگی ها را از تصویر به مفاهیم کلی تری انتزاع می کند که می تواند برای طبقه بندی استفاده شود که از تصویر نهایی مشخص نیست که مدل یک سگ را دیده است.






In this tutorial, you will discover how to develop simple visualizations for filters and feature maps in a convolutional neural network.For this purpose, the  Unet model has been used.

The U-Net model is a simple fully convolutional neural network that is used for binary segmentation i.e foreground and background pixel-wise classification.
This model includes 45 convolution layers and 7 pooling layers, a simple image of the filters of these types of layers is given.

First you will see a visualization of specific filters in a convolutional neural network and then How to develop a visualization for specific feature maps in a convolutional neural network.

Running the example of pooling layers, results in seven plots showing the feature maps from the seven main blocks of the model.

We can see that the feature maps closer to the input of the model capture a lot of fine detail in the image and that as we progress deeper into the model, the feature maps show less and less detail as the model abstracts the features from the image into more general concepts that can be used to make a classification.  it is not clear from the final image that the model saw a dog.

