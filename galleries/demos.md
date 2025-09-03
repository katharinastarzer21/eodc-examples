# Demos Gallery

<div style="display: flex; flex-direction: column; gap: 20px; max-width: 800px;">
<div class="notebook-card" data-tags="Dask eodc SDK" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="https://gateway.dask.org/_static/images/dask-horizontal-white.svg" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Distributed computing with Dask</strong><br>
    This notebook demonstrates how to use the EODC Dask service via Dask Gateway for scalable, distributed data analysis. It covers authentication, cluster creation, scaling, and execution of computations on geospatial datasets stored in S3, including flood and rainfall data examples.
    <div style="margin: 6px 0;">
      <span class="tag">Dask</span><span class="tag">eodc SDK</span>
    </div>
    <a href="../demos/dask.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="Sentinel-2 CSW" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../style/OGC.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>EODC Data Discovery via CSW</strong><br>
    This notebook demonstrates how to use the OGC CSW (Catalogue Service for the Web) endpoint at EODC for data discovery. It shows how to query Sentinel-2 L2A metadata using OWSLib with temporal and spatial filters, and extract file paths for offline access.
    <div style="margin: 6px 0;">
      <span class="tag">Sentinel-2</span><span class="tag">CSW</span>
    </div>
    <a href="../demos/python-csw.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="Sentinel-2" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../style/eodc_logo.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Sentinel 2 - Timeseries analysis</strong><br>
    In this notebook, we will have a closer look at Sentinel2 L2A data over Austria in 2024. The parameters of interest are the SCL, RGB, NDVI, LAI, FAPAR, FCOVER, CAB. They are pre-computed and made available at EODC's s3 objectstore. 
    <div style="margin: 6px 0;">
      <span class="tag">Sentinel-2</span>
    </div>
    <a href="../demos/S2/indices.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="STAC cloud4geo" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="https://d33wubrfki0l68.cloudfront.net/22691a3c3002324451ed99f4009de8aab761e1b7/d24da/public/images-original/stac-01.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Exploring Data with STAC and Xarray</strong><br>
    In this notebook, we will demonstrate how to use the STAC API in conjunction with open-source Python libraries to load data into *Xarray* via *odc-stac*. The objective of this notebook is to showcase the integration of data discovery (using STAC) and data analysis (using Xarray).
    <div style="margin: 6px 0;">
      <span class="tag">STAC</span><span class="tag">cloud4geo</span>
    </div>
    <a href="../demos/cloud4geo_webinar/python-stac-xarray.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="STAC cloud4geo" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="https://d33wubrfki0l68.cloudfront.net/22691a3c3002324451ed99f4009de8aab761e1b7/d24da/public/images-original/stac-01.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Discover Data via the STAC API</strong><br>
    This notebooks prvides an overview n how to access data via the STAC API.
    <div style="margin: 6px 0;">
      <span class="tag">STAC</span><span class="tag">cloud4geo</span>
    </div>
    <a href="../demos/cloud4geo_webinar/python-stac.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="STAC EO-MQS" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../../style/STAC.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Discovering Earth Observation Data with the EO-MQS</strong><br>
    The EO-MQS service is hosted within the C-SCALE federated cloud infrastructure and provides a unified way of discovering Copernicus data available within the federation by making use of the SpatioTemporal Asset Catalog (STAC) specification. The purpose of this notebook is to prvovide a concise introduction on how to use open-source Python libraries to search for geospatial data exposed by the EO-MQS STAC API.
    <div style="margin: 6px 0;">
      <span class="tag">STAC</span><span class="tag">EO-MQS</span>
    </div>
    <a href="../demos/eo-mqs/1-EO-MQS_DataDiscovery.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="STAC EO-MQS" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../../style/STAC.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Analyzing STAC Metadata from the EO-MQS</strong><br>
    This notebook gives you a few examples how you can use tools like `pandas` to make analyses on the queried metadata.
    <div style="margin: 6px 0;">
      <span class="tag">STAC</span><span class="tag">EO-MQS</span>
    </div>
    <a href="../demos/eo-mqs/2-Simple-Metadata-Analysis.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="STAC EO-MQS xarray" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../../style/STAC.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Load Data from the EO-MQS into Xarray</strong><br>
    This notebook demnostrates how data can be accessed via the EO-MQS. Note the primary objective of the EO-MQS is to **discover** the data, the following code is a bonus and slightly out of scope of this demo.
    <div style="margin: 6px 0;">
      <span class="tag">STAC</span><span class="tag">EO-MQS</span><span class="tag">xarray</span>
    </div>
    <a href="../demos/eo-mqs/3-Load-STAC-Items-xarray.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="STAC" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../style/STAC.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Discover Data via the STAC API</strong><br>
    This notbook demonstrates how to access data from the EODC STACK catalogue
    <div style="margin: 6px 0;">
      <span class="tag">STAC</span>
    </div>
    <a href="../demos/STAC/python-stac_DataDiscovery.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="STAC" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Load Data from the EODC STAC catalogue into Xarray</strong><br>
    This notbook demonstrates how to Load Data from the EODC STAC catalogue into Xarray
    <div style="margin: 6px 0;">
      <span class="tag">STAC</span>
    </div>
    <a href="../demos/STAC/python-stac_LoadDataXarray.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="User Story workspace" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../style/eodc_logo.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>User Story: Create EODC Workspace</strong><br>
    John wants to create a user workspace at EODC, as he does not have a object-storage solution himself.
    <div style="margin: 6px 0;">
      <span class="tag">User Story</span><span class="tag">workspace</span>
    </div>
    <a href="../demos/workspaces/demo-create-workspace.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="User Story" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../style/eodc_logo.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>User Story: Load Data</strong><br>
    This notebooks shows how to load your collections in a simple process.
    <div style="margin: 6px 0;">
      <span class="tag">User Story</span>
    </div>
    <a href="../demos/workspaces/demo-load-data.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="User Story" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../style/eodc_logo.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>User Story: Credential Management</strong><br>
    This notebook will outline how you can create user credentials, delete them and get them if you forget them.
    <div style="margin: 6px 0;">
      <span class="tag">User Story</span>
    </div>
    <a href="../demos/workspaces/demo-register-user.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="User Story" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../style/eodc_logo.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>User Story: Registering a Workspace</strong><br>
    John is a PhD student with user collection data stored in a container on Azure blob storage service. 
    <div style="margin: 6px 0;">
      <span class="tag">User Story</span>
    </div>
    <a href="../demos/workspaces/demo-register-workspace.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="User Story openEO" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../style/eodc_logo.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>User Story: Save openEO result to Workspace</strong><br>
    Mia is a data scientist, she wants to have access to the user workspace solution to store user results produced with the openEO Platform service offering.
    <div style="margin: 6px 0;">
      <span class="tag">User Story</span><span class="tag">openEO</span>
    </div>
    <a href="../demos/workspaces/demo-save-results.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="User Story openEO" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../style/eodc_logo.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>User Story: Workspace Sharing</strong><br>
    John creates a user collection by running an openEO process graph. He wants to share this user collection with Nina. Nina wants to visualise John's user collection in a Jupyter Notebook and runs a process graph that uses this as an input collection.
    <div style="margin: 6px 0;">
      <span class="tag">User Story</span><span class="tag">openEO</span>
    </div>
    <a href="../demos/workspaces/demo-share-workspace.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="User Story openEO" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../style/eodc_logo.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>User Story:List Files</strong><br>
    As an openEO Platform user, Mia wants to list all files in her user workspace.
    <div style="margin: 6px 0;">
      <span class="tag">User Story</span><span class="tag">openEO</span>
    </div>
    <a href="../demos/workspaces/demo-show-files.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="User Story STAC" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../style/eodc_logo.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>STAC Modify Process</strong><br>
    This notebooks explains the use of the STAC Modify Process.
    <div style="margin: 6px 0;">
      <span class="tag">User Story</span><span class="tag">STAC</span>
    </div>
    <a href="../demos/workspaces/demo-stac-modify.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="User Story STAC" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../style/eodc_logo.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Workspace Providers</strong><br>
    Workspace Providers are the name of the different underlying object-storage types that are supported by any given backend.
    <div style="margin: 6px 0;">
      <span class="tag">User Story</span><span class="tag">STAC</span>
    </div>
    <a href="../demos/workspaces/demo-workspace-providers.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="ASAR STAC ERS/Envisat" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../../style/Envisat.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Accessing Level-1 and ARD (A)SAR Data from ERS-1/2 and ENVISAT</strong><br>
    This notebook serves as a guide for accessing and downloading the ERS/Envisat (A)SAR Level-1 and ARD datasets. These datasets are made available through the EODC STAC API and Data Access Service, enabling open and free access to end users. The primary goal is to increase the visibility and usability of heritage Earth observation data from the ERS and Envisat missions. This guide will walk you through the steps for discovering, accessing, and downloading the data.
    <div style="margin: 6px 0;">
      <span class="tag">ASAR</span><span class="tag">STAC</span><span class="tag">ERS/Envisat</span>
    </div>
    <a href="../demos/ASAR/ASAR_data_access.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="ASAR openeo ERS/Envisat" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="../../style/Envisat.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Working with ERS_ENVISAT_NRB in OpenEO</strong><br>
    This notebook demonstrates how openEO can be used to access and work with the ERS_ENVISAT_NRB collection. This dataset provides Analysis Ready Data (ARD) derived from ERS and ENVISAT missions. It includes Normalized Radar Backscatter (NRB) products, developed with an aim to be compliant with CEOS ARD specification.
    <div style="margin: 6px 0;">
      <span class="tag">ASAR</span><span class="tag">openeo</span><span class="tag">ERS/Envisat</span>
    </div>
    <a href="../demos/ASAR/ENVISAT_OpenEO.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="GFM STAC" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>GFM data discovery and download</strong><br>
    This notebook demnostrates how GFM data can be accessed and downloaded from th EODC STAC catalog.
    <div style="margin: 6px 0;">
      <span class="tag">GFM</span><span class="tag">STAC</span>
    </div>
    <a href="../demos/GFM/download_gfm_python.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="GFM" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Save GFM results in cloud object store</strong><br>
    In this demo we will show you how to remotely process data on the EODC cluster using dask and save the result in a cloud object store.
    <div style="margin: 6px 0;">
      <span class="tag">GFM</span>
    </div>
    <a href="../demos/GFM/gfm_dask_objectstorage.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="GFM filter" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Refine STAC query using filters</strong><br>
    In this notebook, we demonstrate how to refine the query against the GFM STAC catalogue using the filter STAC API extension
    <div style="margin: 6px 0;">
      <span class="tag">GFM</span><span class="tag">filter</span>
    </div>
    <a href="../demos/GFM/gfm_filter.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="GFM DASK" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>EODC Dask Tutorial</strong><br>
    In this notebook we demonstrate the basics of using Dask on the EODC cluster.
    <div style="margin: 6px 0;">
      <span class="tag">GFM</span><span class="tag">DASK</span>
    </div>
    <a href="../demos/GFM/gfm_maximum_flood_extent_dask.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="GFM STAC" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>GFM maximum flood extent with STAC</strong><br>
    This notebook will demonstrate how to find data using STAC, load it into a xarray object and calculate a result.
    <div style="margin: 6px 0;">
      <span class="tag">GFM</span><span class="tag">STAC</span>
    </div>
    <a href="../demos/GFM/gfm_maximum_flood_extent_local.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="GFM STAC" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Computation of GFM Maximum Flood Extent for a specific area and time of interest</strong><br>
    With this notebook we demonstrate how STAC can be used to find GFM data (ensemble_flood_extent) and derive the maximum flood extent from it.
    <div style="margin: 6px 0;">
      <span class="tag">GFM</span><span class="tag">STAC</span>
    </div>
    <a href="../demos/GFM/gfm_maximum_flood_extent_simple_plot.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="GFM STAC" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Compute maximum flood extent utilizing STAC</strong><br>
    With this notebook, we want to demo how STAC can be used to find GFM ensemble_flood_extent data and derive the maximum flood extent from it.
    <div style="margin: 6px 0;">
      <span class="tag">GFM</span><span class="tag">STAC</span>
    </div>
    <a href="../demos/GFM/gfm_maximum_flood_extent_stac.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="GFM" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Plot GFM flood scene</strong><br>
    This tutorial will show how to plot a part of a flooded GFM scene using an OpenStreetMap basemap as background.
    <div style="margin: 6px 0;">
      <span class="tag">GFM</span>
    </div>
    <a href="../demos/GFM/gfm_plot_flood_scene.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
<div class="notebook-card" data-tags="GFM" style="display: flex; align-items: flex-start; border: 1px solid #cddff1; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
  <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
    <img src="https://european-flood.emergency.copernicus.eu/efas_frontend/assets/img/wms/GFM.svg" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
  </div>
  <div style="flex: 1;">
    <strong>Evaluating Observed Flood Extent from the GFM against Forecast Flood Extent from the EFAS Rapid Flood Mapping layer</strong><br>
    With this notebook, we show how to use the new GFM STAC service to derive the maximum flood extent for a flood event, extract the corresponding forecast product from the EFAS Rapid Flood Mapping layer and perform a simple evaluation.
    <div style="margin: 6px 0;">
      <span class="tag">GFM</span>
    </div>
    <a href="../demos/GFM/gfm_rfm_evaluation.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
  </div>
</div>
</div>