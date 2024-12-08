<h1>Infrastructure Development Schemes Analysis</h1>
<h3>Project Overview: -</h3>
<p>
  In this project, I utilized Power BI in combination with SQL to conduct a comparative and comprehensive analysis of various road development schemes initiated by the Indian government.
The data for this analysis was initially stored in an SQL database, which I imported into Power BI using a DirectQuery connection. Additionally, I integrated supplementary data from web sources, including state-wise and sector-wise GDP growth statistics.
Extensive data cleaning and transformation operations were carried out to prepare the dataset for meaningful visualization. By leveraging various Power BI visuals and creating custom measures, I designed an interactive dashboard that offers both a comprehensive overview and a comparative analysis of the progress and other key aspects of these infrastructure development schemes.
The dashboard evaluates the performance of these schemes at both the state and district levels, examining factors such as completed development works so far, allocated budgets, expenditures, and more. Furthermore, the report explores the impact of infrastructure development on the GDP growth of states and various sectors.
</p>
<h3>Data Source: -</h3>
<ol>
  <li>
    Government State-wise and District-wise Data on Infrastructure Development Schemes:
    <ul>
      <li>This dataset covered schemes such as PMGSY-I, PMGSY-II, PMGSY-III, and RCPLWEA.</li>
      <li>The data was initially stored in an SQL database and imported into Power BI using the DirectQuery connectivity mode.</li>
    </ul>
  </li>
  <li>
    State-wise GSDP Growth Data (2011–2023):
    <ul><li>This dataset was sourced from the web (Wikipedia) and imported into Power BI for analysis.</li></ul>
  </li>
  <li>
    Sector-wise GDP Growth Data (2007–2017):
    <ul><li>This data was stored in an Excel file and imported into Power BI.</li></ul>
  </li>
</ol>
<h3>Tools Used: -</h3>
<ul>
  <li>Power BI desktop</li>
  <li>Power BI query editor</li>
  <li>SQL Server Management Studio</li>
</ul>
<h3>Data Cleaning and Transformation: -</h3>
<p>The data files imported from the web had several inconsistencies that required cleaning and transformation. Below are the key operations performed on each dataset:</p>
<ol>
  <li>
    Government Data of Infrastructure Schemes:
    <ul><li>Concatenated the values from the State and District columns to standardize the data structure.</li></ul>
  </li>
  <li>
    State-wise GSDP Data:
    <ul>
      <li>Extracting the correct values from inconsistent entries.</li>
      <li>Replacing incorrect values with accurate ones.</li>
      <li>Filtering the dataset to retain only the required records for analysis.</li>
    </ul>
  </li>
  <li>
    Sector-wise GDP Growth Data:
    <ul>
      <li>Removed unnecessary rows and columns to focus only on relevant information.</li>
      <li>Simplified sector names by replacing long names with shorter, more concise alternatives.</li>
      <li>Unpivoted the data columns for easier analysis and visualization in Power BI.</li>
      <li>Converted the data type of values in the Growth column to percentages for accurate representation.</li>
    </ul>
  </li>
</ol>
<h3>Metrics Used:</h3>
<ul>
  <li>Total sanctioned roads & Total completed roads.</li>
  <li>Total sanctioned bridges & Total completed bridges.</li>
  <li>Road completion % and Bridge completion %</li>
  <li>Allocated budget and expenditure</li>
  <li>Budget Utilization %</li>
  <li>Total sanctioned and completed road length (in km)</li>
  <li>Allocated Budget per km and Expenditure per km</li>
  <li>GSDP Growth % </li>
  <li>Cumulative GDP growth (%)</li>
</ul>
<h3>Key Insights: -</h3>
<ul>
  <li>Total Sanctioned Roads = 188032</li>
  <li>Total Completed Roads = 181046</li>
  <li>Total Sanctioned Bridges = 11929</li>
  <li>Total Completed Bridges = 9183</li>
  <li>Allocated Budget = 38686.69 lakhs</li>
  <li>Overall Expenditure = 329064.61 lakhs</li>
  <li>Completed Work = 98.13%</li>
  <li>Budget Utilization = 85.10%</li>
</ul>
<h3>Scheme-wise Statistics: -</h3>
<table>
  <tr>
    <th>Scheme Name</th>
    <th>Sanctioned Roads</th>
    <th>Completed Roads</th>
    <th>Sanctioned Bridges</th>
    <th>Completed Bridges</th>
    <th>Total Completed Work</th>
    <th>Budget Utilization</th>
  </tr>
  <tr>
    <td>PMGSY-I</td>
    <td>164608</td>
    <td>163476</td>
    <td>7456</td>
    <td>7136</td>
    <td>99.16%</td>
    <td>94.95%</td>
  </tr>
  <tr>
    <td>PMGSY-II</td>
    <td>6665</td>
    <td>6571</td>
    <td>759</td>
    <td>746</td>
    <td>98.56%</td>
    <td>89.89%</td>
  </tr>
  <tr>
    <td>PMGSY-III</td>
    <td>15412</td>
    <td>10082</td>
    <td>3009</td>
    <td>868</td>
    <td>59.44%</td>
    <td>58.94%</td>
  </tr>
  <tr>
    <td>RCPLWEA</td>
    <td>1347</td>
    <td>917</td>
    <td>705</td>
    <td>433</td>
    <td>65.79%</td>
    <td>68.31%</td>
  </tr>
</table>
<ol>
  <li>
    PMGSY (Phase I):
    <ul>
      <li>
        Road Development:
        <p>Significant progress was made in states like Rajasthan, Uttar Pradesh, Bihar, Odisha, and Madhya Pradesh.</p>
      </li>
      <li>
        Bridge Development:
        <p>Most bridge construction activities were concentrated in Assam, Bihar, Madhya Pradesh, and Maharashtra.</p>
      </li>
    </ul>
  </li>
  <li>
    PMGSY (Phase II):
    <ul>
      <li>
        Road Development:
        <p>The highest road development was observed in Uttar Pradesh, Odisha, and Tamil Nadu.</p>
      </li>
      <li>
        Bridge Development:
        <p>The majority of bridge construction was carried out in Madhya Pradesh.</p>
      </li>
    </ul>
  </li>
  <li>
    PMGSY (Phase III):
    <ul>
      <li>
        Road Development:
        <p>Significant road development occurred in Uttar Pradesh, Odisha, Tamil Nadu, Madhya Pradesh, and Karnataka.</p>
      </li>
      <li>
        Bridge Development:
        <p>Most bridge construction was focused in Madhya Pradesh, Bihar, and Karnataka.</p>
      </li>
    </ul>
  </li>
  <li>
    RCPLWEA:
    <ul>
      <li>
        Road Development:
        <p>Major road development was observed in Chhattisgarh, Jharkhand, Andhra Pradesh, and Bihar.</p>
      </li>
      <li>
        Bridge Development:
        <p>Most bridges were constructed in Jharkhand, Bihar, and Maharashtra.</p>
      </li>
    </ul>
  </li>
</ol>

<h3>Impact of infrastructure development schemes on Sectoral GDP growth:</h3>
<ul>
  <li>Transport, Storage and communication = 208.22%</li>
  <li>Construction = 123.86%</li>
  <li>Trade, Hotels and restaurant = 112.19%</li>
  <li>Financing, insurance, real estate, and business services = 170.82%</li>
</ul>

<h3>Learning Outcomes:</h3>
<p>In addition to performing data cleaning, transformation, and visualization, I also learned a new concept: the DirectQuery connection.</p>
<p>I imported data from an SQL database using the DirectQuery connectivity mode. DirectQuery is a mode in Power BI that connects directly to the data source without importing the data into the Power BI model. In this mode, the Data View option is unavailable, meaning any data changes must be made at the original data source—in this case, the SQL database. To accommodate this, I made all necessary changes to the development schemes-related data in SQL Server Management Studio (SSMS).</p>
<p>While I didn’t face performance issues due to the relatively small dataset, I learned that DirectQuery mode generally has slower performance compared to Import mode, especially with larger datasets or complex queries.</p>
<p>Additionally, this project involved importing data from various sources, including an SQL database, web data (Wikipedia), and Excel files, which introduced me to the Composite Model feature of Power BI. The Composite Model allows combining data from multiple sources, enabling greater flexibility and more robust analysis.</p>













