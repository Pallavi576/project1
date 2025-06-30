🧠 Project Overview
AI Nutrition Assistant is a smart and interactive tool designed to assist users in identifying food items and retrieving their nutritional information in real-time. It supports both text input and image recognition, providing a convenient way for users to make healthier food choices. The application uses deep learning and real-world nutrition data from authoritative sources to deliver accurate and fast results.

🎯 Objectives
To build an intelligent assistant that recognizes food using either a user’s text input or an uploaded image.

To educate users on the nutritional value of everyday food items.

To encourage healthy eating habits through accessible and accurate nutritional data.

📖 Problem Statement
Many individuals struggle with identifying the nutritional content of the food they consume daily. With fast-paced lifestyles and increasing health concerns, there’s a need for a quick and intelligent solution that can:

Recognize food visually through images.

Provide verified nutrition facts without the need for manual searches.

Work offline (partially) with AI support and online (via API) for real-time nutrition data.

⚙️ How It Works
Image Mode:

Users upload an image of food.

A pre-trained deep learning model (MobileNetV2) predicts the food type.

The predicted label is sent to the USDA API to retrieve nutrition facts.

Text Mode:

Users enter the name of a food item manually.

The assistant fetches the corresponding nutrition data from the USDA database.

🌐 Data Source
The project uses the USDA FoodData Central API, a reliable government-backed database that provides detailed nutrient data for thousands of food items. The API includes:

Macronutrients like Protein, Fat, and Carbohydrates.

Micronutrients such as Sodium, Vitamins, and Minerals.

Standardized food descriptions and measurements.

🧪 Use Cases
📱 Fitness Apps: Can be integrated into health & diet tracking apps.

🧑‍⚕️ Dietitians: Useful for quick nutritional assessments during consultations.

🛒 Smart Grocery Assistants: Could extend to scanning food labels for nutritional analysis.

🧑‍🎓 Educational Tool: Ideal for teaching students about food science and AI applications in health.

🚧 Limitations and Future Improvements
Current Limitations:

Pre-trained model (MobileNetV2) may misclassify non-standard food items.

Relies on internet connectivity for fetching nutrition data via API.

Top-5 predictions only — not custom trained for food-specific datasets.

Planned Enhancements:

Build a custom food image classifier for better accuracy.

Integrate voice input and OCR (for reading labels).

Create a Streamlit or mobile app interface for better UX.

Add calorie tracking and meal planning features.

💡 Unique Highlights
Combines computer vision and nutrition science.

Utilizes public health APIs for data accuracy.

Offers an interactive CLI experience, which can be expanded into a web/mobile interface.

Encourages awareness about healthy eating with minimal user input.

