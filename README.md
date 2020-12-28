# lcvp_webaccess

This project serves the purpose of providing an easy-to-use webaccess for the LCVP-Dataset.<br/>Access it here: <a href="http://lcvp.familie-haid.com">lcvp.familie-haid.com</a>

If you encounter any problems or got feature-requests, please open a new issue!<br/>I appreciate any support, espacially as the website is still in beta.

<h3>About</h3>
<p>
  This is the <b>unofficial</b> webview of the <a href="https://idata.idiv.de/ddm/Data/ShowData/1806"><b>Leipzig Catalogue of Vascular Plants (LCVP)</b></a> from the <a href="https://www.idiv.de/">German Centre for Integrative Biodiversity Research (iDiv) Halle-Jena-Leipzig</a>.
  <br>Abstract: "The Leipzig Catalogue of Vascular Plants (LCVP) is as far as we know the most updated and resolved list of plant names and their synonyms of all known vascular plant species on this planet."
  <br>The dataset is uptodate as of 25.12.2020 and was not modified. I did some additional processing and indexing.
  <br>All data on this website is licensed under CC BY 4.0 (like the <a href="https://idata.idiv.de/ddm/Data/ShowData/1806">original publication</a>).
  <br>If you find any issues or want to request an new feature, please do so <a href="https://github.com/mhaid/lcvp_webaccess/issues/">here on github</a>.
</p>

<h3>Reason</h3>
<p>
  I created this website to make it easier for everyone to access LCVP-data.
  <br>I greatly appreciate the work of Martin Freiberg, Alessandro Gentile, Alexande Zizka, and Marten Winte as it is considered the most up-to-date and best-resolved list of vascular plant species names on the planet.
</p>

<h3>Details</h3>
<p>
  To view details of an order, family or species, please search for it using the <a href="http://lcvp.familie-haid.com/search.php">Basic search</a>. Alternatively, you can navigate to the desired entry via one of the three lists.
  <br>The detail page of an accepted species lists all other species taxa that are used as synonyms. The page of a synonymous species taxon contains the link to the accepted species taxon.
  <br>Each family and species detail page contains a link to the detail page of the parent item(s).
  <br>All family pages show a pie chart of the distribution of the species statuses.
</p>

<h3>Stats</h3>
<p>
  Right now only basic statistics about families are implemented:
  <br>-> Number of all species in a family;
  <br>-> Number of accepted species in a family;
  <br>-> Number of synonym species in a family;
  <br>-> Number of untesolved species in a family (taxon could be either valid or synonym, but the information available does not allow a definitive decision);
  <br>-> Number of external species in a family (outside the scope of LCVP but useful to keep on this updated list).
</p>
<p>
  A comparison with 'The Plant List'-publication is not implemented in yet, but can be found in the original LCVP-publication.
</p>
