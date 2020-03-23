# Задача

**Требуется:** предложить модель, сегментирующую окурок сигареты на фотографии.  
  
**Вход:** фотография 512x512x3.  
**Выход:** маска окурка сигареты 512x512.  
**Метрика:** [Dice coefficient](https://en.wikipedia.org/wiki/S%C3%B8rensen%E2%80%93Dice_coefficient).  

# Данные

Ссылка на скачивание данных: [link](https://www.immersivelimit.com/datasets/cigarette-butts).

Данные представляют из себя набор синтетически сгенерированных фотографий окурков сигарет и маски, определяющей их на фотографии, а также координаты ограничивающего их бокса.

Доступные данные разделены на несколько папок:  
- `real_test` содержит фотографии 512x512x3;  
- `train/images` содержит фотографии 512x512x3;  
- `train/coco_annotations.json` содержит аннотации в формате [COCO](http://cocodataset.org/#format-data);  
- `val/images` содержит фотографии 512x512x3;  
- `val/coco_annotations.json` содержит аннотации в формате [COCO](http://cocodataset.org/#format-data).



