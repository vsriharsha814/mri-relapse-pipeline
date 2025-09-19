# Medulloblastoma Resection Analysis Pipeline

A machine learning pipeline for analyzing pre- and post-operative MRI scans to predict medulloblastoma relapse risk and quantify surgical resection extent using AI models.

## Problem Statement

Medulloblastoma is a highly malignant brain tumor that requires surgical resection. While complete resection is ideal for optimal patient outcomes, it is not always feasible due to the tumor's proximity to critical brain structures such as the brainstem, cranial nerves, and major blood vessels. Incomplete resection significantly increases the risk of relapse, but current methods for quantifying resection extent and predicting relapse risk are limited.

This project investigates whether the extent of surgical resection, quantified via pre- and post-operative MRI using AI models, can predict relapse risk and aid in clinical decision-making. The pipeline aims to:

- Quantify surgical resection extent from pre- and post-operative MRI scans
- Predict relapse risk based on resection completeness and tumor characteristics
- Provide clinical decision support for surgical planning and post-operative care
- Develop robust AI models that can handle the complexity of brain tumor imaging

## Project Goals

- **Resection Quantification**: Develop AI models to accurately measure surgical resection extent from pre- and post-operative MRI scans
- **Relapse Prediction**: Build predictive models that can assess relapse risk based on resection completeness and tumor characteristics
- **Clinical Integration**: Create tools that can be integrated into clinical workflows for surgical planning and post-operative monitoring
- **Data Preprocessing**: Build a comprehensive pipeline for brain tumor MRI data preprocessing using MONAI
- **Model Development**: Implement and test modern sequence models (Mamba, Transformer-based architectures) for medical imaging analysis
- **Performance Evaluation**: Establish clinical validation metrics and compare different model architectures

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- MONAI team for excellent medical imaging tools
- Mamba model developers for state-space sequence modeling
- Medical imaging research community for open datasets and methodologies
- Neurosurgeons and oncologists for clinical insights and validation
- Medulloblastoma research community for advancing treatment outcomes

## Contact

For questions or collaborations, please open an issue or contact the project maintainers.

---

**⚠️ Disclaimer**: This project is for research purposes only. Any clinical applications should undergo proper validation, regulatory approval, and clinical trials. The models and predictions should not be used for clinical decision-making without proper medical supervision and validation.