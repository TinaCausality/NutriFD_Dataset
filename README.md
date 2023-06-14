# NutriFD Database

We have established the NutriFD database, as described in our research paper [link to the paper](https://arxiv.org/abs/2304.04775). The NutriFD database is a comprehensive collection of food-nutrition data, food-disease treatment inference scores, food-disease association inference scores, food information,and disease information. All data used in the code can be downloaded in https://drive.google.com/file/d/1S_m0D99Kor00rSs5WajHUPLdwAVykW6L/view?usp=drive_link. NutriFD Web can be found in the link https://nutrifd.dedyn.io. 

## Database Construction

The NutriFD database was constructed through the following steps:

1. **Food-nutrition datasets collection and food names integration**: Refer to the notebook `food_nutrition.ipynb` for details on collecting food-nutrition datasets and integrating food names.

2. **Food-compound-disease datasets establishment**: The notebooks `Food_disease_association.ipynb` and `Food_disease_treatment.ipynb` provide the code and instructions for establishing the food-compound-disease datasets.

3. **Disease similarity features establishment**: The notebook `disease_features.ipynb` outlines the process of establishing three types of disease similarity features.

4. **Disease names integration**: The notebook `Disease_integration.ipynb` covers the integration of disease names.

5. **Datasets evaluations**: The notebooks `Asso_machine_learning.ipynb` and `Treatment_machine_learning.ipynb` contain the code and evaluations for the datasets.

Please refer to the respective notebooks for more detailed information on each step.

## Usage

To utilize the NutriFD database, follow these steps:

1. Clone this repository to your local machine:
git clone [https://github.com/your-username/nutrifd-database.git](https://github.com/TinaCausality/NutriFD_Dataset.git)

2. Download related data in https://drive.google.com/file/d/1S_m0D99Kor00rSs5WajHUPLdwAVykW6L/view?usp=drive_link.

2. Install the necessary dependencies as specified in the notebook files.

3. Open the notebooks using Jupyter Notebook or any compatible environment and run the code cells to reproduce the database construction process.

Feel free to explore and utilize the NutriFD database for your research or projects. For any inquiries or issues, please contact us at tinalalala12580@gmail.com.

