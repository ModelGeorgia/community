## Image/Video Generation

[Stability AI API](https://dreamstudio.com/api/) - [StableStudio UX](https://dreamstudio.com/studio/) - [Image Generator](https://dreamstudio.ai/generate)

For hero images, input-output visualizations and training resources.  
Themes examples: Last Airbender and Marvel Comics APIs

Project areas:  

1. Save generated images using GitHub Actions (or a CoLab script) with the [Stability.AI API Platform](https://platform.stability.ai/), the [GetImg Stable Diffusion API](https://getimg.ai/tools/api), the upcoming [Midjourney API](https://tokenizedhq.com/midjourney-api/), and/or <a href="https://replicate.com/docs/get-started/nextjs">Replicate.com NextJS</a>.

2. Automate pulling UN Comtrade input-output data using GitHub Actions to create static files to use with our global search filters. Our <a href="/data-pipeline/international/">International data prep</a> page  

3. Find and embed/fork existing [United Nations Comtrade data visualizations](https://comtradeplus.un.org/Visualization/Labs). 

4. [Apache ECharts 3D Globe](https://echarts.apache.org/examples/en/editor.html?c=globe-layers&gl=1). Could also update timeline slider in OpenStreetMaps so earthquake locations change as slider moves on <a href="https://model.earth/country-data/map/">3D Globe with Timeline</a>. Here's a version with [changing country boundaries](/mbgl-timeslider/demo/).


## Input-Output Visualization

Our modeled images approximate reality as a tool for understanding international commerce. By combining UN import-export data with Large Language Models (LLM) trained using location photos, prompts driven by NAICS data are used to approximate locations.

<img src="/io/coders/img/DreamStudio_NAICS_111339_-_Other_Noncitrus_Fruit_Farming_closeu_2d1ab81d-6281-44bf-8fb5-efd584f0461a.png" style="width:100%">
NAICS 111339 - Other Noncitrus Fruit Farming closeup, Ecuador landscape
<br>

<img src="/io/coders/img/DreamStudio_NAICS_111339_Other_Noncitrus_Fruit_Farming_closeup__4bb46868-c345-423c-b291-34f636f9c9d9.png" style="width:100%">
NAICS 111339 "Other Noncitrus Fruit Farming" closeup in Ecuador


<!--
3. Add to our [interface in Figma](https://www.figma.com/file/mVZUSQCMBsIMu9bp7Y8qsS/Neighborhood-Impact-Footprint?node-id=18%3A6) for showing everyone's real-time score for 24 impact areas. Install [Figma Unify](https://www.figma.com/community/plugin/1009866256233241860/Unify%3A-Figma-to-React%2C-React-Native-and-HTML%2FCSS) to convert Figma components into clean React.  
4. Explore [NextJS](https://nextjs.org/) using our [Engine-Storybook](https://github.com/localsite/engine-storybook) repo.  
-->




<img src="https://i.annihil.us/u/prod/marvel/i/mg/3/40/4bb4680432f73/standard_fantastic.jpg" style="float:right; margin:0 0 20px 20px">

Create a friendly interface for students and educators using the EPA indicator sets of Air, Water, Land, Energy, Wealth and Health.  <a href="../../../io/charts/inflow-outflow/#set=air&indicators=GHG,GCC,MGHG,OGHG,HRSP,OZON,SMOG,HAPS">View inflow-outflow catgories</a>

Work in the [Engine-Storybook](https://github.com/localsite/engine-storybook) repo, which includes a typescript branch.

<!--
Or use our blank React <a href="https://github.com/modelearth//amplifyapp">AmplifyApp</a>.--><!-- (The older category set json resides in docs/static/json thanks to Alikah )-->
<!--We've documented  <a href="https://model.earth/aws/amplify/">AWS Amplify set up steps</a>.-->


<!--as Primary and Secondary columns in <a href="../community-data/us/indicators/LCIA_Indicator_sets.csv">LCIA_Indicator_sets.csv</a> and in the [Bio-Modeling Branch](https://github.com/modelearth/useeior/blob/Bio-Modeling/inst/extdata/USEEIO_LCIA_Indicators.csv).  
-->

Here’s an <a href="https://last-airbender-api.herokuapp.com/">Airbender API</a> you can use to relate the four “nation” categories to characters.  

Pull dynamically from the <a href="https://developer.marvel.com/documentation/images">Marvel Character API</a> and use D3 to add interactivity - <a href="https://planet.live/marvel/">Planet.live&nbsp;Marvel&nbsp;sample</a>  

Get creative! Explore other movie/book themes and brainstorm how environmental indicators could be an integral part of multiple forms of entertainment. Here's a potential background image. Try some [Glassmorphism](https://davidlevai.com/tailwind-glassmorphism)!  

<div class="lazy bgimg bgimg-notfixed" data-src="img/bkgd.jpg" style="opacity:.85">
    <a href="../../../io/charts/inflow-outflow/#set=water&indicators=WATR,ACID,EUTR,ETOX"><img src="../../../io/charts/inflow-outflow/img/bkgd.jpg" style="opacity:.95;width:100%"></a>
</div>
