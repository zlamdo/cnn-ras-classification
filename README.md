# CNN klasifikace robotickych a autonomnich systemu

Repozitar obsahuje MATLAB skripty pouzite v diplomove praci zamerene na klasifikaci robotickych a autonomnich systemu pomoci konvolucnich neuronovych siti (CNN).

---

## Pouzite modely

| Model | Popis |
|---|---|
| AlexNet | Zakladni CNN architektura pouzita pro prvotni experimenty |
| ResNet-18 | Rezidualni sit s nizsi hloubkou |
| ResNet-50 | Hlubsi rezidualni sit s bottleneck vrstvami |
| MobileNetV2 | Optimalizovana architektura pro efektivni zpracovani |
| CNN + SVM | Kombinace extrakce priznaku z CNN a klasifikace pomoci SVM |

---

## Pozadovane MATLAB toolboxy

- Deep Learning Toolbox
- Deep Learning Toolbox Model for AlexNet Network
- Deep Learning Toolbox Model for ResNet-18 Network
- Deep Learning Toolbox Model for ResNet-50 Network
- Deep Learning Toolbox Model for MobileNet-v2 Network
- Statistics and Machine Learning Toolbox
- Parallel Computing Toolbox

---

## Pouzite prostredi

| Komponenta | Verze |
|---|---|
| MATLAB | R2024a |
| Operacni system | macOS / Windows |
| GPU akcelerace | NVIDIA CUDA |

---

## Obsah repozitare

```text id="0p7a2x"
alexnet/
resnet18/
resnet50/
mobilenetv2/
cnn_svm/
results/
