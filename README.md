# BigForma

# README: BigForma - Advanced Database Management for Course Recommendations

## Overview  
**BigForma** is a project designed to tackle the challenges of managing and analyzing big data for an **online platform** aimed at helping users find the most compatible studies and institutions. This platform aggregates and organizes information about courses across **France** and from **Coursera**, enabling users to make informed decisions based on their preferences and needs.  

## Features  
- **Web Scraping**:  
  The project employs the **Selenium** library and **ChromeDriver** to scrape course-related data efficiently. It extracts information such as course names, presenters, platforms, and relevant metadata from various sources.  
- **Advanced Database Management**:  
  The collected data is stored and managed in a structured format to support robust search functionalities and advanced recommendations.  
- **Recommendation System**:  
  A GUI is under development to provide users with personalized course recommendations based on their input.  

## Objectives  
1. To simplify the process of finding suitable courses and institutions.  
2. To leverage big data techniques for creating a comprehensive and user-friendly course database.  
3. To integrate modern tools like Selenium for automating data collection.  

## How to Use  
1. Install the required dependencies listed:
    selenium==4.15.0
    pandas==2.1.3
    numpy==1.26.1
    sqlalchemy==2.1.1        
3. Set up **ChromeDriver** (ensure it matches your Chrome version).  
4. Run the provided Python scripts to scrape data from French platforms and Coursera.  
5. Access the processed data through the database or the planned GUI.  

## Challenges  
- **Big Data Management**: Handling and organizing large volumes of course data efficiently.  
- **Compatibility**: Ensuring the scraped data aligns with the needs of diverse user groups.  
- **Integration**: Combining data from multiple sources into a unified database.  

## Future Work  
- Develop a fully functional **GUI** for personalized course recommendations.  
- Expand scraping capabilities to cover more platforms and course providers.  
- Optimize the database for faster searches and improved scalability.  

## License  
This project is licensed under the [MIT License](LICENSE).  


