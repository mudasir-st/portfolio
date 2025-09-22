{% raw %}
<style>
.maps-row {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
  justify-content: center;
  margin-top: 20px;
}

.maps-row div {
  max-width: 150px;      /* thumbnail size */
  text-align: center;
  flex: 1 1 150px;       /* allows shrink/grow in row */
}

.maps-row img {
  width: 100%;           /* fills container */
  height: auto;
  border: 1px solid #ddd;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.2);
  margin-bottom: 8px;
  cursor: pointer;
}
</style>
{% endraw %}




# Welcome to My Portfolio 

## About Me

I am Mudasirullah Stanikzai, a geoscience and GIS/geospatial data science professional with over 3 years of experience applying GIS in the earth science field.  
Throughout my academic and professional journey, I have applied GIS technology to both research and applied projects.  

I hold a Master’s degree in Earth Resources Science and am currently pursuing a Graduate Certificate in CyberGIS and Geospatial Data Science.  

This portfolio highlights a selection of my personal and academic projects in cartography, remote sensing, and geospatial data science.  
It does not reflect all of my work — if you would like to learn more about my GIS work, please reach out via the **Contact** section.  

## ArcGIS Projects
### 1. Cartography and Static Maps

<div class="maps-row">

  <div>
    <a href="assets/img/Kentucky_Static_Map.jpg" class="glightbox" data-title="Kentucky Static Map">
      <img src="assets/img/Kentucky_Static_Map.jpg" alt="Kentucky Static Map">  
    </a>
    <p>This static map of Kentucky highlights major geographic and infrastructural features...</p>
  </div>

  <div>
    <a href="assets/img/Indianapolis_Drainage_Map.jpg" class="glightbox" data-title="Indianapolis Soil Drainage Map">
      <img src="assets/img/Indianapolis_Drainage_Map.jpg" alt="Indianapolis Soil Drainage Map">
    </a>
    <!--
      This map illustrates soil drainage classes across the Indianapolis region using SSURGO data 
      from the USDA NRCS. By joining spatial and tabular datasets, soils were categorized into different classes.
      The map supports applications in urban planning, stormwater management, and environmental analysis.
    -->
  </div>

  <div>
    <a href="assets/img/I-65_Linear_Referencing_Map.jpg" class="glightbox" data-title="I-65 Linear Referencing Map">
      <img src="assets/img/I-65_Linear_Referencing_Map.jpg" alt="I-65 Linear Referencing Map">
    </a>
    <p>This map demonstrates linear referencing along I-65 highway using M-value based stationing...</p>
  </div>

</div>



### Web and Interactive Maps
####  1. Ohio River NH₃-N Concentrations (1976–2024)
 
This interactive web map presents annual mean concentrations of ammonia as nitrogen (NH₃-N) mg/L in the Ohio River from 1976 to 2024. The project integrates Python-based data cleaning (see files and data in the repository), ArcGIS Pro for spatial processing, temporal analysis with time-enabled layers, and web GIS publishing via ArcGIS Online to visualize long-term water quality trends.
<iframe 
  src="https://univofillinois.maps.arcgis.com/apps/mapviewer/index.html?webmap=2fff2b5c34ba475aac118e481e43f316" 
  width="700" 
  height="500" 
  frameborder="0" 
  style="border:0;" 
  allowfullscreen>
</iframe>






## Geospatial Data Science Projects

Coming soon!



## Contact
- 📩 Email: [mudasir2.stanikzai@gmail.com](mailto:mudasir2.stanikzai@gmail.com)  
- 🔗 LinkedIn: [linkedin.com/in/mudasir-stanikzai](https://linkedin.com/in/mudasir-stanikzai)  
- 🐙 GitHub: [github.com/mudasir-st](https://github.com/mudasir-st/portfolio) 

