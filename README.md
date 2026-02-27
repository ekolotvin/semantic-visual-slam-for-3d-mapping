# Integration of Semantic Segmentation into Visual SLAM
![11](https://github.com/user-attachments/assets/2cf86d77-cca1-4169-b44c-926d316dd18f)
![Снимок экрана 2026-02-28 010250](https://github.com/user-attachments/assets/2525095e-fda9-4f1d-9fc8-0d6ff1241c7a)

## В этом проекте модель семантической сегментации интегрируется в пайплайн Visual SLAM для построения трёхмерной семантически размеченной реконструкции сцены.
Для каждого входного кадра:
Предсказывается семантическая маска;
Маска интегрируется в SLAM;
Строится 3D карта сцены с семантическими метками.
