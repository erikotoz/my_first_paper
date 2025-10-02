Название | Ссылка | Краткий вывод | Обозначение |
| -------- | ------ | ------------------ | ----------- |
| Flow-Guided Feature Aggregation (FGFA) | [Link](https://arxiv.org/abs/1703.10025) | Классический VOD с агрегацией по оптическому потоку; воспроизводимый baseline. | ✅✅ |
| FGFA (официальный код) | [Link](https://github.com/msracver/Flow-Guided-Feature-Aggregation) | Репозиторий от авторов, удобен для адаптации под индустриальные данные. | ✅✅ |
| Deep Feature Flow (DFF) | [Link](https://arxiv.org/abs/1611.07715) | Ускорение за счёт ключевых кадров и протяжки фич; быстрый видеобазис. | ✅ |
| DFF (официальный код) | [Link](https://github.com/msracver/Deep-Feature-Flow) | Готовые скрипты; полезно для real-time сценариев. | ✅ |
| Relation Distillation Networks (RDN) | [Link](https://arxiv.org/abs/1908.09511) | Учёт отношений между RoI по времени; прирост mAP на VID. | ✅ |
| SELSA | [Link](https://arxiv.org/abs/1907.06390) | Семантическая агрегация по всей последовательности; сильный baseline. | ✅✅ |
| MEGA | [Link](https://arxiv.org/abs/2003.12063) | Память + глобально-локальная агрегация контекста; SOTA на VID. | ✅✅ |
| MEGA (PyTorch код) | [Link](https://github.com/Scalsol/mega.pytorch) | Воспроизводимый код, удобен для наших экспериментов. | ✅✅ |
| Spatial-Temporal Memory Networks (STMN) | [Link](https://arxiv.org/abs/1712.06317) | Пространственно-временная память; релевантно для VOD. | ✅ |
| T-CNN / Tubelets | [Link](https://arxiv.org/abs/1604.02532) | Исторически значимый подход с «трубками»; базовый ориентир. | ✅ |
| Detect-to-Track & Track-to-Detect (D&T) | [Link](https://arxiv.org/abs/1710.03958) | Совмещает детекцию и трекинг; укрепляет устойчивость боксов. | ✅ |
| TransVOD | [Link](https://arxiv.org/abs/2201.05047) | Временной трансформер поверх Deformable DETR; сильная линия VOD. | ✅✅ |
| TransVOD (репозиторий) | [Link](https://github.com/SJTU-LuHe/TransVOD) | Официальный код; готовая база для сравнения. | ✅✅ |
| TransVOD++ | [Link](https://arxiv.org/abs/2305.15415) | Улучшения к TransVOD; лучшее соотношение точность/скорость. | ✅ |
| TransVOD++ (репозиторий) | [Link](https://github.com/qianyuzqy/TransVOD_plusplus) | Код и конфиги для воспроизводимых экспериментов. | ✅✅ |
| TubeDETR | [Link](https://arxiv.org/abs/2203.16434) | Поиск пространственно-временных «трубок»; полезно для клиповой агрегации. | ✅ |
| VisTR (Video Instance Segmentation) | [Link](https://arxiv.org/abs/2011.14503) | End-to-end transformer для VIS; релевантен для видео-сегментации. | ✅✅ |
| VisTR (код) | [Link](https://github.com/YuqingWang1029/VisTR) | Официальная реализация; готовая точка старта. | ✅✅ |
| MaskTrack R-CNN (YouTube-VIS) | [Link](https://arxiv.org/abs/1905.04804) | Базовый VIS-подход; важен как сравнимый ориентир. | ✅ |
| MaskTrack R-CNN (репозиторий) | [Link](https://github.com/youtubevos/MaskTrackRCNN) | Практичный код под YouTube-VIS; удобен для адаптации. | ✅✅ |
| SeqFormer (VIS) | [Link](https://arxiv.org/abs/2112.08275) | Последовательностная агрегация масок; сильный VIS baseline. | ✅ |
| SeqFormer (код) | [Link](https://github.com/wjf5203/SeqFormer) | Репозиторий с рецептам; пригодно для наших тестов. | ✅ |
| TeViT (VIS) | [Link](https://arxiv.org/abs/2204.08412) | Эффективное временное внимание; вариант для видеомасок. | ✅ |
| IDC: Identity-Consistent Aggregation (VOD) | [Link](https://openaccess.thecvf.com/content/ICCV2023/html/Deng_Identity-Consistent_Aggregation_for_Video_Object_Detection_ICCV_2023_paper.html) | Агрегация с учётом идентичности; устойчива к окклюзиям. | ✅✅ |
| Video Swin Transformer (backbone) | [Link](https://arxiv.org/abs/2106.13230) | Сильный видеобэкбон; хорошо сочетается с VOD/VIS головами. | ✅ |
| Video Swin (код) | [Link](https://github.com/SwinTransformer/Video-Swin-Transformer) | Официальная реализация; ускоряет прототипирование. | ✅✅ |
| YOLOX (one-stage) | [Link](https://arxiv.org/abs/2107.08430) | Современная one-stage база для видео-пайплайнов. | ✅ |
| YOLOX (репозиторий) | [Link](https://github.com/Megvii-BaseDetection/YOLOX) | Стабильный код, удобный для продакшн-пайплайнов. | ✅ |
| RT-DETR (real-time DETR) | [Link](https://arxiv.org/abs/2304.08069) | Реал-тайм детектор; хорош как image-baseline в видеопайплайне. | ✅ |
| RT-DETR (код) | [Link](https://github.com/lyuwenyu/RT-DETR) | Репозиторий с обучением/инфером; пригоден для интеграции. | ✅ |
| DINO / Deformable DETR family | [Link](https://arxiv.org/abs/2203.03605) | Сильная DETR-база; полезно для видео-детекции/сегментации. | ✅ |
| Mask DINO (семейство) | [Link](https://arxiv.org/abs/2206.02777) | Объединение детекции и сегментации; релевантно для VIS. | ✅ |
| Detectron2 | [Link](https://github.com/facebookresearch/detectron2) | Фреймворк CV; быстрый старт для наших голов. | ✅✅ |
| MMDetection | [Link](https://github.com/open-mmlab/mmdetection) | Богатый зоопарк моделей и рецептов; стандарт для OD. | ✅✅ |
| MMTracking | [Link](https://github.com/open-mmlab/mmtracking) | Трекинг + VOD/VIS пайплайны; удобно для экспериментов. | ✅✅ |
| YouTube-VIS (dataset) | [Link](https://youtube-vos.org/dataset/vis/) | Ключевой датасет для видео instance-сегментации. | ✅ |
| OVIS (dataset) | [Link](https://arxiv.org/abs/2111.07950) | VIS с сильными окклюзиями; стресс-тест ассоциации. | ✅ |
| ImageNet VID (dataset) | [Link](https://image-net.org/challenges/LSVRC/2017/) | Классический бенчмарк VOD; 30 классов, аннотация по кадрам. | ✅ |
| BDD100K (dataset) | [Link](https://www.bdd100k.com/) | 100K видеороликов; разнообразные сцены/погоды/время суток. | ✅ |
| UA-DETRAC (dataset) | [Link](https://detrac-db.rit.albany.edu/) | Транспортные сцены; релевантно для индустриальных кейсов. | ✅ |
| MOT17 / MOT20 (tracking datasets) | [Link](https://motchallenge.net/) | Полезны для модулей ассоциации; не прямая VOD/VIS метрика. | ✅ |
| DanceTrack (tracking dataset) | [Link](https://dance-track.github.io/) | Сложные изменения вида/движения; полезно для устойчивости. | ✅ |
| ByteTrack (tracker) | [Link](https://arxiv.org/abs/2110.06864) | Простой и сильный трекер; полезен в связке с OD. | ✅ |
| StrongSORT (tracker) | [Link](https://arxiv.org/abs/2202.13514) | Усиленная ассоциация; может улучшить стабильность трубок. | ✅ |
| TrackFormer (MOT) | [Link](https://arxiv.org/abs/2101.02702) | DETR-подобные track-queries; релевантно для видео-ассоциации. | ✅ |
| TransTrack (MOT) | [Link](https://arxiv.org/abs/2012.15460) | Joint detection & tracking; близко к нужной постановке. | ✅ |
| MOTR (E2E MOT) | [Link](https://arxiv.org/abs/2105.03247) | End-to-End трекинг на основе DETR; полезно для ассоциации. | ✅ |
| Deformable DETR | [Link](https://arxiv.org/abs/2010.04159) | Быстро сходится и масштабируется; база для TransVOD. | ✅ |
| Video K-Net (VIS) | [Link](https://arxiv.org/abs/2204.04656) | Унифицированная сегментация с видеорасширением; вариант для VIS. | ✅ |
| Mask2Former (image/video ext.) | [Link](https://arxiv.org/abs/2112.01527) | Общая парадигма сегментации; есть видеорасширения в экосистемах. | ✅ |
| TAO / AVA-Kinetics (контекст датасетов) | [Link](https://arxiv.org/abs/2005.10356) | Длинные видеопоследовательности для OD/объектов; скорее контекст. | ✅ |
| SlowFast (action recognition) | [Link](https://arxiv.org/abs/1812.03982) | Экшен-бэкбон; вне прямой VOD/VIS задачи. | ❌ |
| I3D / R(2+1)D (action) | [Link](https://arxiv.org/abs/1711.11248) | Бэкбоны для экшенов; не сравнимы по нашим метрикам. | ❌ |
| Two-Stream Networks | [Link](https://arxiv.org/abs/1406.2199) | Исторический action-baseline; мимо текущей постановки. | ❌ |
| ResNet | [Link](https://arxiv.org/abs/1512.03385) | Базовый image-бэкбон; без видеокомпоненты. | ❌ |
| Vision Transformer (ViT) | [Link](https://arxiv.org/abs/2010.11929) | Общая архитектура; без специфики VOD/VIS. | ❌ |
| Swin Transformer (image) | [Link](https://arxiv.org/abs/2103.14030) | Иерархический image-бэкбон; без видеоагрегации. | ❌ |
| DETR (original) | [Link](https://arxiv.org/abs/2005.12872) | Базовый трансформер-детектор; без видеорасширений. | ❌ |
| YOLOv5 (image) | [Link](https://github.com/ultralytics/yolov5) | Инженерный image-детектор; не видео-метрики. | ❌ |
| PP-YOLOE (image) | [Link](https://arxiv.org/abs/2203.16250) | Сильный image one-stage; нет видеоэкспериментов. | ❌ |
| Cascade Mask R-CNN (image) | [Link](https://arxiv.org/abs/1906.09756) | Image-instance сегментация; вне видео-сравнения. | ❌ |
| SAM (segment anything) | [Link](https://arxiv.org/abs/2304.02643) | Foundation-модель сегментации; нецелевой для VOD/VIS метрик. | ❌ |
| CLIP (vision-language) | [Link](https://arxiv.org/abs/2103.00020) | Мультимодальная предобученная модель; не про VOD/VIS. | ❌ |
| Detic (open-vocab image) | [Link](https://arxiv.org/abs/2201.02605) | Open-vocab детектор; не видео-бенчмарки. | ❌ |
| Survey: Video Object Detection (2019) | [Link](https://www.mdpi.com/2076-3417/9/15/3201) | Обзор до «эпохи трансформеров»; полезен как фон. | ✅ |
| Survey: Transformers for Video Understanding (2024) | [Link](https://arxiv.org/abs/2405.05584) | Обзор бэкбонов/архитектур; контекст, без прямых VOD/VIS метрик. | ✅ |
| Review: Video Instance Segmentation | [Link](https://arxiv.org/abs/2304.09854) | Систематизация VIS-подходов; помогает выбрать головы. | ✅ |
| UA-DETRAC (ориг. статья) | [Link](https://arxiv.org/abs/1511.04136) | Первоисточник датасета и протоколов; пригодно для описания. | ✅ |
| BDD100K (ориг. статья) | [Link](https://openaccess.thecvf.com/content_CVPR_2020/papers/Yu_BDD100K_A_Diverse_Driving_Dataset_for_Heterogeneous_Multitask_Learning_CVPR_2020_paper.pdf) | Подробности разметки/задач; полезно для репликации. | ✅ |
| YouTube-VIS (ориг. статья) | [Link](https://arxiv.org/abs/1905.04804) | Вводит VIS-задачу и протокол; базовый референс. | ✅ |
| Practical VOD with Regression Tracker | [Link](https://www.sciencedirect.com/science/article/pii/S092427162100099X) | Детектор + регрессионный трекер; прикладной baseline. | ✅ |
| Crop-based Detection for UA-DETRAC | [Link](https://lab-work.github.io/download/gloudemans2021crop.pdf) | Простая эвристика обрезки; полезно для транспорта/потоков. | ✅ |
| Efficient One-Stage VOD (family) | [Link](https://arxiv.org/abs/2402.09241) | Упор на эффективность; хорош для продакшн-ограничений. | ✅ |
| MMEngine + OpenMMLab stack | [Link](https://github.com/open-mmlab) | Экосистема фреймворков/инструментов; ускоряет эксперименты. | ✅✅ |
