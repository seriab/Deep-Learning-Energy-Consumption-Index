# **Towards an Energy Consumption Index for Deep Learning Models**

The growing global demand for computational resources, particularly in Artificial Intelligence (AI) applications, raises increasing concerns about energy consumption and its environmental impact. This study introduces a newly developed energy consumption index that evaluates the energy efficiency of Deep Learning (DL) models, providing a standardized and adaptable approach for various models.

Convolutional neural networks, including both classical and modern architectures, serve as the primary case study to demonstrate the applicability of the index. Furthermore, the inclusion of the Swin Transformer, a state-of-the-art and modern non-convolutional model, highlights the adaptability of the framework to diverse architectural paradigms. 

This study analyzes the energy consumption during both training and inference of representative DL architectures, including AlexNet, ResNet18, VGG16, EfficientNet-B3, ConvNeXt-T, and Swin Transformer, trained on the Imagenette dataset using TITAN XP and GTX 1080 GPUs. Energy measurements are obtained using sensor-based tools, including OpenZmeter (v2) with integrated electrical sensors. Additionally, software-based tools such as CarbonTracker (v1.2.5) and CodeCarbon (v2.4.1) retrieve energy consumption data from computational component sensors. 

The results reveal significant differences in energy efficiency across architectures and GPUs, providing insights into the trade-offs between model performance and energy use. By offering a flexible framework for comparing energy efficiency across DL models, this study advances sustainability in AI systems, supporting accurate and standardized energy evaluations applicable to various computational settings.
