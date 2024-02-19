# InBloom
![inbloom_cover](https://github.com/ChaseNaidoo/InBloom-Portfolio-Project/assets/125469506/7d88dae9-8f60-4d9f-92dc-3bf3281d8ccd)

## Overview
InBloom addresses the challenge of providing an easy and effective way for individuals, particularly farmers, to determine the health of their plants through AI-driven plant disease detection.

## Project Inspiration
It all started with a news segment. A story about a single, unemployed mother of one. Living in the rural areas with restricted access to food she would often go days without eating just so she could give whatever she could to her newborn. However, despite the effort and sacrifice the child is ended up malnourished.
This affected me deeply. I thought if she could not get to access to affordable and nutritious food. What if we could bring the food to her? What if she could grow crops in her own backyard?
Coming from a background in biotechnology, I have knowledge in the difficulties of growing crops due to disease and infections. Having researched the very organisms that cause these diseases it is essential to detect plant disease as early as possible to prevent further spread.
By leveraging artificial intelligence we can do just that. InBloom attempts to provide users with a completely free and open-source solution to predict the health of a plant through image processing.

- [Portfolio Landing Page](https://chasenaidoo.github.io/)
- [Portfolio Project Blog](https://www.linkedin.com/posts/cameron-chase-naidoo_artificialintelligence-ai-pythonprogramming-activity-7164997873510563840-75z0?utm_source=share&utm_medium=member_desktop)

## Installation
To install and set up the project, follow these steps:
1. Clone the repository: `git clone https://github.com/ChaseNaidoo/InBloom-Portfolio-Project`
2. Install dependencies: `npm install`
4. Start the server: `npm run start`

## Usage
1. `cd plant_disease_model/frontend`
2. Start the server: `npm run start`
3. Open your browser and navigate to [http://localhost:3000](http://localhost:3000)
4. In another terminal, `cd plant_disease_model/api`
5. Run `./main.py`
6. To train a custom model, modify `training/inbloom_datasets` to include your datasets
7. Modify `main.py` in `plant_disease_model/api` to include class names
8. Modify `training_model.py` in `training` to include the correct number of classes
9. `cd plant_disease_model/training`
10. Run `./training_model.py`

# Screenshots
![feature2](https://github.com/ChaseNaidoo/InBloom-Portfolio-Project/assets/125469506/eb392c75-0559-4696-be12-229cea7497b0)
![feature3](https://github.com/ChaseNaidoo/InBloom-Portfolio-Project/assets/125469506/401e0106-c1a1-481b-ac3f-6cfb0ccd9fe1)

## Contributing
If you'd like to contribute to the project, please follow these steps:
1. Fork the repository
2. Create a new branch: `git checkout -b feature_branch`
3. Make your changes and commit them: `git commit -am 'Add new feature'`
4. Push to the branch: `git push origin feature_branch`
5. Submit a pull request

## Related Projects
- [Potato Disease Classification](https://github.com/codebasics/potato-disease-classification)
- [Plant AI](https://github.com/soumyajit4419/Plant_AI)

## Authors
[Cameron Chase Naidoo](https://www.linkedin.com/in/cameron-chase-naidoo/)

## Licensing
This project is licensed under the MIT License.
