## Travel time to NHS organisations

The following page and accompanying GitHub repository contain the initial proof of concept and exploratory analysis for the design of a holistic and interactive mapping tool to support decision-making in health and social care.

A mapping tool could support national and regional commissioning strategies by facilitating the placement of new services and the reconfiguration of existing ones. It could also contribute to the NHS agenda for tackling health inequalities by enabling evidence-based decision-making by providing insight on how the availability of health and social care services is influenced by sociodemographic factors.

Using open-source software and publicly accessible datasets we calculate the travel time, with different modes of transport, to varying NHS healthcare services in London and Cambridge. We highlight the challenges of estimating accurate travel times and possible approaches to overcome these. 

Data sources: [NHS Digital](https://digital.nhs.uk/services/organisation-data-service/file-downloads/gp-and-gp-practice-related-data), [Uber Movement](https://movement.uber.com/)

<hr class="nhsuk-u-margin-top-0 nhsuk-u-margin-bottom-6">

<div class="nhsuk-warning-callout">
  <h3 class="nhsuk-warning-callout__label">
    Data Quality<span class="nhsuk-u-visually-hidden">:</span>
  </h3>
  <p>Data Quality placeholder. 
  </p>
</div>

### Walking time to GP practices in Cambridge

<p>Click on an indvidual marker for the GP practice name, code, address, and contact information.</p>

<iframe width= "500" height="500"  src="images/folium/cambridge_map_no_travel.html" style="border:none;"></iframe>

<div class="row">
  <div class="column">
    <img src="images/png/cambridge_osmnx_nodes.png" width="500" height="500">
  </div>
  <div class="column">
    <img src="images/png/cambridge_node_coloured.png" width="500" height="500">
  </div>
</div>

<div class="row">
  <div class="column">
    <img src="images/png/cambridge_isochromes_coloured.png" width="500" height="500">
  </div>
  <div class="column">
    <iframe width= "500" height="500"  src="images/folium/cambridge_map_travel.html" style="border:none;"></iframe>
  </div>
</div>

### Driving time between a GP Practice and a Hospital in central London

<p>
Placeholder text. 
</p>

<div class="row">
  <div class="column">
    <img src="images/png/london_osmnx_nodes.png" width="500" height="500">
  </div>
  <div class="column">
    <iframe width= "500" height="500"  src="images/folium/route_map.html" style="border:none;"></iframe>
  </div>
</div>

<div class="nhsuk-action-link">
  <a class="nhsuk-action-link__link" href="">
    <svg class="nhsuk-icon nhsuk-icon__arrow-right-circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" aria-hidden="true">
      <path d="M0 0h24v24H0z" fill="none"></path>
      <path d="M12 2a10 10 0 0 0-9.95 9h11.64L9.74 7.05a1 1 0 0 1 1.41-1.41l5.66 5.65a1 1 0 0 1 0 1.42l-5.66 5.65a1 1 0 0 1-1.41 0 1 1 0 0 1 0-1.41L13.69 13H2.05A10 10 0 1 0 12 2z"></path>
    </svg>
    <span class="nhsuk-action-link__text">Download this dataset (.csv)</span>
  </a>
</div>

## About this page

This page is built using end-to-end open source analytical tools including: [The NHS Digital Service Manual](https://service-manual.nhs.uk/), [python](https://nhs-pycom.net/), [plotly](https://plotly.com/python/), [folium](http://python-visualization.github.io/folium/), [geopy](https://geopy.readthedocs.io/en/stable/), [beautiful soup](https://www.crummy.com/software/BeautifulSoup/), [github.io](https://pages.github.com/), and [github actions](https://github.com/features/actions).

<div class="nhsuk-action-link">
  <a class="nhsuk-action-link__link" href="https://github.com/nhsx/open-analytics-template">
    <svg class="nhsuk-icon nhsuk-icon__arrow-right-circle" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" aria-hidden="true">
      <path d="M0 0h24v24H0z" fill="none"></path>
      <path d="M12 2a10 10 0 0 0-9.95 9h11.64L9.74 7.05a1 1 0 0 1 1.41-1.41l5.66 5.65a1 1 0 0 1 0 1.42l-5.66 5.65a1 1 0 0 1-1.41 0 1 1 0 0 1 0-1.41L13.69 13H2.05A10 10 0 1 0 12 2z"></path>
    </svg>
    <span class="nhsuk-action-link__text">Find out how to build your own open analytics pipeline</span>
  </a>
</div>

If you have any suggestions or questions, email: <a href="mailto:mattia.ficarelli@nhsx.nhs.uk">mattia.ficarelli@nhsx.nhs.uk</a> or <a href="mailto:paul.carroll@nhsx.nhs.uk">paul.carroll@nhsx.nhs.uk</a>

<hr class="nhsuk-u-margin-top-0 nhsuk-u-margin-bottom-6">