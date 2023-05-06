## Asteroid Diameter Prediction for Earth Impact Assessment
This is a machine learning project that predicts the diameter of asteroids to assess their potential impact on Earth. The data used for this project is from NASA's Jet Propulsion Laboratory (JPL) [Click Here for the Original Dataset!](https://ssd.jpl.nasa.gov/tools/sbdb_query.html) [Click Here to download the Dataset!](https://www.kaggle.com/datasets/basu369victor/prediction-of-asteroid-diameter/download?datasetVersionNumber=5)

![](https://www.nasa.gov/sites/default/files/thumbnails/image/nasa-logo-web-rgb.png)
![](https://media.cnn.com/api/v1/images/stellar/prod/200629132529-nasa-dart-spacecraft-liciacube.jpg?q=w_1600,h_900,x_0,y_0,c_fill)

### Brief Overview
Asteroids have long held a significant role in the rich history of our solar system, as they have existed since its very formation. Throughout the ages, these celestial bodies have impacted Earth on multiple occasions, resulting in mass extinctions and leaving indelible imprints on our planet. Consequently, esteemed space organizations such as NASA diligently monitor asteroids due to their potential threat to Earth, and comprehending their behavior and trajectory is of paramount importance in developing efficacious mitigation strategies.

Precisely determining the diameter of an asteroid is a critical factor in comprehending its potential impact on Earth and formulating appropriate mitigation strategies. Even a minor disparity in diameter can prove to be the demarcation between a benign atmospheric entry and a calamitous impact with far-reaching consequences.

However, accurately measuring the diameter of an asteroid is a challenging task, as it is difficult to directly observe these celestial bodies. As a result, machine learning algorithms offer a potential strategy for forecasting asteroid features based on current data.

### Data Description
The asteroid data is provided by NASA’s Jet Propulsion Laboratory (JPL) which is a federally funded research and development center managed for NASA by Caltech. JPL maintains a database of asteroid observations and orbital information called the Small-Body Database Browser (JPL, n.d.) (“Victor Basu Kaggle Data,” n.d.).

The SBDB has an extensive amount of data about asteroids and other minor bodies in our solar system, including their names, designations, sizes, masses, densities, rotation periods, and albedos. It also includes information on these objects’ orbits, such as eccentricity, inclination, semimajor axis, and perihelion and aphelion distances. The database is divided into tables and sections, and users may query and download the data in a variety of forms, including CSV, JSON, and XML. The database is updated regularly with new observations and discoveries, and is publicly accessible through the JPL website.

Asteroid Features can be divided into 2 main categories: Orbital and Spectral. In the original set of features the number of Spectral features are 6 times the amount of Orbital Features. More Details about each asteroid feature can be found in the Report.

### Setup and Usage
To set up this project, you need to:

1. Clone the repository to your local machine. <br>
2. Download the dataset from the link above and place it in the data directory of the cloned repository.<br>
3. Install the required packages using pip or conda. Required packages include:<br>
    - pandas<br>
    - numpy<br>
    - matplotlib<br>
    - seaborn<br>
    - sklearn<br>
    - xgboost<br>
4. Run all the codes in the /codes folder for Data Cleaning, Modeling and Evaluation.<br>
5. Read the Report.html for detailed analysis and conclusions.

### Contributing
If you want to contribute to this project, you can:

- Submit a pull request to add new features or fix bugs.
- Report an issue if you find a bug or have a suggestion for improvement.

