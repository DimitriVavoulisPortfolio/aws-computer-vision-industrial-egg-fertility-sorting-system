# Computer Vision Industrial Egg Fertility Sorting System

## Project Overview

This project is a production-ready YOLOv8n-based Computer Vision system for egg fertility detection, designed for high-speed, single-column conveyor belt operations in industrial settings. The system provides accurate and efficient sorting of eggs into fertile and infertile categories, optimized for speed and cost-effectiveness.

### Key Features

- Pre-trained YOLOv8n model for egg fertility detection
- Optimized for high-speed conveyor belt operations
- Designed for low compute costs to maximize scalability
- Comprehensive testing with both individual images and batch processing
- Correction mechanism for handling multiple detections
- Designs for AWS serverless architecture for potential future deployment

## Project Structure

1. **Data processing and Training**: Scripts for data preparation and model training
2. **YOLOv8n_egg_fertility_model**: Trained YOLOv8n model for egg fertility detection
3. **Testing scripts**: Scripts for testing the model, including individual image and batch processing
4. **AWS Implementation Design**: Proposed AWS serverless architecture for deployment

## Documentation

- **MODEL.md**: Detailed information about the model architecture, training process, and performance
- **PROCESS.md**: Comprehensive overview of the development process and implementation plan
- **AWS-PLAN-DESIGN-AND-COST-REPORT.md**: Detailed report on the proposed AWS implementation and associated costs

## Model Performance

- **Accuracy: 1.00**
- **Precision: 1.00**
- **Recall: 1.00**
- **F1-score: 1.00**

Speed Performance:
- Preprocess: 3.0ms per image
- Inference: 10.0ms per image
- Postprocess: 2.0ms per image
- Total processing time: 15.0ms per image

## Quick Start Guide

1. Clone the repository:
   ```
   git clone https://github.com/DimitriVavoulisPortfolio/aws-computer-vision-industrial-egg-fertility-sorting-system.git
   cd aws-computer-vision-industrial-egg-fertility-sorting-system
   ```

2. Install dependencies:
   ```
   pip install ultralytics torch numpy opencv-python
   ```

3. To test the model with individual images:
   ```
   python test_single_image.py
   ```

4. To test the model with datasets:
   ```
   python yolov8n-egg-detection-test-script.py
   ```
DISCLAIMER: The paths for the model and test images need to be specified by the user.

## Future Work

- Implement AWS deployment
- Create API for real-time egg fertility prediction
- Optimize model performance for even faster processing
- Develop a user interface for system monitoring and control

## License

This project is licensed under the Apache-2.0 license - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please open an issue in this repository or contact [Dimitri Vavoulis](mailto:dimitrivavoulis3@gmail.com).
