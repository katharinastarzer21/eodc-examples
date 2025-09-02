# Tutorials


<div style="display: flex; flex-direction: column; gap: 20px; max-width: 800px;">

<!-- # AI4SAR data access -->

<div class="notebook-card" style="display: flex; align-items: flex-start; border: 1px solid #BAE3FA; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
    <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
      <img src="../style/AI4SAR.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
    </div>
    <div style="flex: 1;">
      <strong>AI4SAR data access</strong><br>
      This notebook demonstrates how to access and visualize AI4SAR Sigma0 (VV and VH) SAR data via a STAC API. It covers searching and filtering collections, loading data into xarray using odc.stac, reprojecting to custom or original CRS, and displaying scaled grayscale images for selected scenes.
      <div style="margin: 6px 0;">
         <span class="tag">AI4SAR</span><span class="tag">Sigma0</span><span class="tag">STAC</span>
      </div>
      <a href="AI4SAR_access_data.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
    </div>
  </div>


<!-- Demo Argo Workflow - Submit Custom -->

<div class="notebook-card"  style="display: flex; align-items: flex-start; border: 1px solid #BAE3FA; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
    <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
      <img src="../style/Argo.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
    </div>
    <div style="flex: 1;">
      <strong>Demo Argo Workflow - Submit Custom</strong><br>
      This notebook demonstrates how to configure and interact with an Argo Workflow service using the eodc SDK. It shows how to set up service credentials, define custom workflows in code using Hera, submit them to the Argo server, and retrieve workflow logs for monitoring.
      <div style="margin: 6px 0;">
         <span class="tag">Argo Workflow</span><span class="tag">eodc SDK</span><span class="tag">Hera</span>
      </div>
      <a href="eodc_sdk_argo.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
    </div>
  </div>

<!-- Access Austrian Ground Motion data via OGC API - Features (WFS) -->

<div class="notebook-card"  style="display: flex; align-items: flex-start; border: 1px solid #BAE3FA; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
    <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
      <img src="../style/OGC.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
    </div>
    <div style="flex: 1;">
      <strong>Access Austrian Ground Motion data via OGC API - Features (WFS)</strong><br>
      This notebook shows how the Ground Motion data over Austria can be loaded from the EODC OGC API and how to visualize it.
      <div style="margin: 6px 0;">
         <span class="tag">WFS</span><span class="tag">OGC API</span>
      </div>
      <a href="Ground_Motion_WFS.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
    </div>
  </div>


<!-- Connect to OGC API - Features service -->

<div class="notebook-card"  style="display: flex; align-items: flex-start; border: 1px solid #BAE3FA; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
    <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
      <img src="../style/OGC.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
    </div>
    <div style="flex: 1;">
      <strong>Connect to OGC API - Features service</strong><br>
      This notebook demonstrates how to access and query YIPEEO vector data exposed through the OGC API - Features service. It shows how to list public collections, authenticate with EODC credentials to access protected datasets, filter and query features , and visualize the results in a GeoDataFrame with maps.
      <div style="margin: 6px 0;">
         <span class="tag">OGC API</span><span class="tag">YIPEEO</span><span class="tag">Authentication</span>
      </div>
      <a href="read_yipeeo_data.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
    </div>
  </div>

  <!-- Harmonized Landsat and Sentinel-2 L2F Analysis -->

<div class="notebook-card"  style="display: flex; align-items: flex-start; border: 1px solid #BAE3FA; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
    <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
      <img src="../style/STAC.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
    </div>
    <div style="flex: 1;">
      <strong>Harmonized Landsat and Sentinel-2 L2F Analysis</strong><br>
      This notebook demonstrates how to search, load, and visualize Harmonized Landsat 8 and Sentinel-2 L2F (Level 2F) data using STAC and the ODC ecosystem. We query the EO Data Cube STAC API, retrieve scenes for a given spatial and temporal extent, and work with data subsets using xarray and dask for efficient handling of large datasets.
      <div style="margin: 6px 0;">
         <span class="tag">Sentinel-2</span><span class="tag">Landsat 8</span><span class="tag">STAC</span><span class="tag">OGC API</span>
      </div>
      <a href="sen2like.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
    </div>
  </div>

  <!-- Harmonized Landsat and Sentinel-2 L2F Analysis - NDVI computation -->

<div class="notebook-card"  style="display: flex; align-items: flex-start; border: 1px solid #BAE3FA; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
    <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
      <img src="../style/STAC.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
    </div>
    <div style="flex: 1;">
      <strong>Harmonized Landsat and Sentinel-2 L2F Analysis - NDVI computation</strong><br>
      This notebook demonstrates how to search and access Harmonized Landsat and Sentinel-2 L2F data via the EODC STAC API. It shows how to load spectral bands with odc.stac, compute NDVI from red (B04) and NIR (B08) bands using Dask for scalable processing, and visualize the results with matplotlib.
      <div style="margin: 6px 0;">
         <span class="tag">Sentinel-2</span><span class="tag">Landsat 8</span><span class="tag">STAC</span><span class="tag">NDVI</span>
      </div>
      <a href="sen2like-ndvi.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
    </div>
  </div>

  <!-- Reading Sentinel-2 L2A Data from a Remote STAC Catalog -->

<div class="notebook-card"  style="display: flex; align-items: flex-start; border: 1px solid #BAE3FA; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
    <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
      <img src="../style/STAC.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
    </div>
    <div style="flex: 1;">
      <strong>Reading Sentinel-2 L2A Data from a Remote STAC Catalog</strong><br>
      This notebook illustrates how to query and access Sentinel-2 L2A data from Microsoft’s Planetary Computer STAC catalog. It applies spatial, temporal, and quality filters, selects the least cloudy scene, retrieves a visual asset, and uses Rasterio and PIL to crop, warp, and display the image over a defined area of interest.
      <div style="margin: 6px 0;">
         <span class="tag">Sentinel-2</span><span class="tag">Planetary Computer</span><span class="tag">STAC</span>
      </div>
      <a href="Sentinel-2.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
    </div>
  </div>


  <!-- Wetland Extent Monitoring with Sentinel-1 SAR -->

<div class="notebook-card"  style="display: flex; align-items: flex-start; border: 1px solid #BAE3FA; border-radius: 6px; padding: 14px 20px; background-color: #f9fbfe; box-shadow: 1px 1px 4px #dfeaf5;">
    <div style="width: 100px; height: 100px; flex-shrink: 0; display: flex; align-items: center; justify-content: center; background-color: #fff; border: 1px solid #e0eaf5; border-radius: 6px; overflow: hidden; margin-right: 32px;">
      <img src="../style/STAC.png" alt="Notebook Thumbnail" style="max-width: 100%; max-height: 100%; object-fit: contain;">
    </div>
    <div style="flex: 1;">
      <strong>Wetland Extent Monitoring with Sentinel-1 SAR</strong><br>
      This notebook shows how to access and visualize wetland extent datasets derived from Sentinel-1 SAR via a STAC API. It demonstrates downloading open-water and inundated-vegetation products, stacking them into time series with xarray, and interactively exploring wetland dynamics through temporal visualization using ipywidgets.
      <div style="margin: 6px 0;">
         <span class="tag">Sentinel-1</span><span class="tag">SAR</span><span class="tag">STAC</span>
      </div>
      <a href="wetland-explorer.ipynb" style="text-decoration: none; color: #1d70b8; font-weight: bold;">View Notebook</a>
    </div>
  </div>
