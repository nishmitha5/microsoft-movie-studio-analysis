# Microsoft Movie Studio Launch Analysis

This project analyzes movie data to provide actionable insights for the launch of Microsoft's new movie studio. It evaluates top movie genres, box office performance, and audience reception to help Microsoft make informed decisions about content creation.

## Table of Contents
- [Project Overview](#project-overview)
- [Business Problem](#business-problem)
- [Data Sources](#data-sources)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. By analyzing top genres, box office performance, and user ratings for different genres, we can leverage data from IMDb's `title.basics`, `title.ratings`, and Box Office Mojo's `movie_gross` datasets. This analysis will provide actionable insights for Microsoft to consider when developing new movies.

## Business Problem
Microsoft needs to identify high-performing movie genres that will maximize their return on investment in the movie industry. The analysis answers key business questions:
1. **Genre Performance**: Which genres generate the highest average box office gross?
2. **Genre Profitability**: Which genres offer the highest potential profit margins?
3. **Genre Trends**: Are there emerging genres with significant growth?

## Data Sources
- **IMDb**: Movie titles, release years, genres, and user ratings.
- **Box Office Mojo**: Domestic and international box office gross data.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- IMDb datasets
- Box Office Mojo datasets

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/nishmitha5/microsoft-movie-studio-analysis.git

2. Navigate to the project directory:

cd microsoft-movie-studio-analysis

3.Install the required dependencies:

pip install -r requirements.txt

## Usage
1. Load the datasets from IMDb and Box Office Mojo.
2. Run the data cleaning and preprocessing script:

python data_preprocessing.py

3. Visualize the results using the results_visualization.py script:

python results_visualization.py

## Results
# Top Performing Genres: Action, Adventure, Comedy, and Animation.
# Highest Box Office Year: 2016 had the highest total box office revenue, with Adventure, Animation, and Comedy genres leading the charts.
# User Ratings: Animation, Documentary, and Fantasy received the highest average ratings.
These insights provide Microsoft with a strategic advantage in producing high-grossing, popular movies​(Final_Microsoftmovies_p…).

## Contributing
Contributions are welcome! Please fork the repository and create a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License.

