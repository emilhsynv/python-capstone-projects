# Python Capstone Projects  

This repository contains my final projects for the **Python for Everybody Specialization**. 
These projects focus on **Retrieving, Processing, and Visualizing Data** using Python and SQLite.  

## 🚀 Projects Overview  

### 📌 [Page Ranker: Search Spider & Page Ranker](pagerank/README.md)  
A web crawler that stores webpage data in an SQLite database and ranks pages using PageRank. It allows incremental crawling and visualizes the link structure.  

✅ **Tech Stack:** Python, SQLite, JSON, Web Scraping  
✅ **Key Features:**  
   - 📡 Webpage crawling & link mapping  
   - 🔢 PageRank algorithm for ranking pages  
   - 📊 JSON-based visualization of links  

✅ **Run Commands:**
	```
	python spider.py  # Crawl webpages
	python sprank.py  # Compute PageRank
	python spjson.py  # Generate visualization 
	```
### 📌 [GeoData: Google Places API & Data Visualization](geodata/README.md)  
Uses the Google Places API to geocode university locations, store them in an SQLite database, and visualize them on Google Maps.

✅ **Tech Stack:** Python, SQLite, Google API, JavaScript
✅ **Key Features:**
   - 📍 Fetches and caches geolocation data
   - 🗄️ Stores locations in an SQLite database
   - 🗺️ Interactive Google Maps visualization

✅ **Run Commands:**
	```
	python geoload.py  # Fetch geolocation data  
	python geodump.py  # Export data to JavaScript  
	open where.html    # View locations on Google Maps  
	```

### 📌 [Roster: Roster Database Management](roster/README.md)  
A database-driven project that processes user-course-role data from JSON and organizes it in an SQLite database.
✅ **Tech Stack:** Python, SQLite, JSON
✅ **Key Features:** 
   - 🏫 Manages user-course-role relationships
   - 📂 Prevents duplicate entries using constraints
   - 🔄 Loads and updates data dynamically

✅ **Run Commands:**
	```
	python rosterdb.py
	```
🚀 **How to Run**
1. Ensure Python & SQLite3 are installed
2. Clone the repository:
	```
	git clone https://github.com/emilhsynv/python-capstone-project.git  
	cd python-capstone-project
	```
3. Navigate to a project folder and run the script
4. Check "rosterdb.sqlite" in DB Browser for SQLite
5. Reset database if needed:
   ```
   rm rosterdb.sqlite  # Mac/Linux
   del rosterdb.sqlite  # Windows
   ```
   
### 📝 **Notes**
   - You can inspect and modify the SQLite database using DB Browser for SQLite.
   - Make sure to set up your Google API key in geoload.py if using "GeoData" Project.
   
✅ **Great for learning Python, SQLite, Web Scraping, API integration, and database management!** 🚀
