Genomes
========

.. raw:: html

  <div class="dlp">
    <h1>Genomes</h1>
    <section class="main">
      <!-- Section: Data -->
      <div class="data-tab" id="tab1">
        <div class="large">
          <p>
            Genomes are received on a regular basis from a multitude of sources (GenBank, RefSeq,
            Collaborator Request, etc.). Our signature PATRIC annotation is generated via the RAST (Rapid Annotation
            Subsystems Technologies) Pipeline, resulting in a consistently annotated set of genomes in which meaningful
            comparisons can be made within and across taxonomic boundaries. We also maintain the original annotations
            from GenBank to allow users to explore and compare annotation differences. In addition, we automatically
            gather, parse, and curate over 60 various associated metadata attributes, such as isolation source
            , geographic location, and host. Find out how to search for genomes of interest in our
            <a href="https://docs.patricbrc.org/user_guides/organisms_taxon/genome_table.html" target="_blank">Genomes Tab User Guide</a>.
          </p>
        </div>

        <div class="group">
          <div class="col span-8 append-1">
            <div class="data-box" id="dlp-genomes-genomeStatus-header">
              <h3 class="ribbon-title">Genome Status</h3>
              <div id="dlp-genomes-genomeStatus">
                <div class="chart"></div>
              </div>
            </div>
          </div>

          <!-- Number of genomes (Two-value line chart ) -->
          <div class="col span-13 append-1">
            <div class="data-box" id="dlp-genomes-numberGenomes-header">
              <h3 class="ribbon-title">Number of Bacterial Genomes</h3>
              <div id="dlp-genomes-numberGenomes">
                <div class="chart"></div>
              </div>
            </div>
          </div>

          <!-- Three tabs with a vertical bar chart. -->
          <div class="col span-13 last">
            <div class="tabbed" id="dlp-genomes-chart">
              <ul class="tab-headers no-decoration inline no-underline-links">
                <li class="ui-state-active"><span data-href="#dlp-genomes-chart-tab1">Host</span></li>
                <li><span data-href="#dlp-genomes-chart-tab2">Isolation Country</span></li>
              </ul>

              <div class="data-box" id="dlp-genomes-chart-tab1">
                <p class="desc">Top 5 Bacterial Hosts</p>
                  <div class="top-5">
                    <div class="chart"></div>
                  </div>
              </div>

              <div class="data-box hidden" id="dlp-genomes-chart-tab2">
                <p class="desc">Top 5 Isolation Countries</p>
                <div class="top-5">
                  <div class="chart"></div>
                </div>
              </div>

            </div><!-- / tabbed -->
          </div>
        </div><!-- / group -->

        <div class="data-box popular-box tabbed hover-tabs no-underline-links">
          <h3 class="ribbon-title">Select Genomes</h3>
          <div class="group">
          </div>
          <p class='down'><a class="double-arrow-link" href="/view/Taxonomy/2#view_tab=genomes">View All PATRIC Genomes</a></p>
        </div>
      </div>

      <!-- Section: Tools -->

      <!-- Section: Process -->
      <div class="data-tab" id="tab3">
        <div class="data-box">
          <h3 class="ribbon-title">How Do We Process and Clean Up Our Data?</h3>
            <img alt="How Do We Process and Clean Up Our Data?" src="https://docs.patricbrc.org/_static/website/data_landing_pages/genomes.jpg" />
        </div>
      </div>

      <!-- Section: Download -->
    </section>
  </div>

