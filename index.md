# Welcome!

## About Me
![me + bog ol' oak](img/nate_tree.JPG)
I am a Project Manager for the Balch Fire Lab and The North Central Regional Invasive Species and Climate Change ([NC RISCC](https://nc-riscc.org/)). Prior to joining the Balch Fire Lab, I worked at the National Ecological Observatory Network (NEON) as a botanist in the [Southeast US](https://www.neonscience.org/impact/observatory-blog/getting-know-neon-domains-ozarks-complex). My previous research focused on assessing genomic variation and habitat suitability for the invasive species, Johnsongrass (*Sorghum halepense*). I received my MS in Biology from the University of Alabama, and my BS in Evolution and Ecology from Ohio State University.

## Data Exploration
Below are assignments from the CU Boulder Earth Analytics Data Science Course

### American Golden Plover Migration Mapping
Investigating the migration patterns of the American golden plover (*Pluvialis dominica*), a bird with an ~24,000 km (~15,000 miles) long yearly migration journey [(1)](https://www.frontiersin.org/journals/ecology-and-evolution/articles/10.3389/fevo.2021.710007/full). Their southern migration route even contains a 3000-5000 km stretch of flight that is entirely over the Atlantic Ocean, meaning these birds cannot stop to rest or feed during this time [(2)](https://www.jstor.org/stable/1366605?casa_token=wtKsQEdXUHwAAAAA%3AM9SB-dQYZ8tHxZH8ErOAosejJCVK5YAF-7ZFgPzXZKqZGBY9flhzqmcCUrz53s2OdZ3rIriJK7n8rJ4yHzNZswPSChv3XFyVbuYgkGRfKBKrE2006hqF).

#### Little bird, big journey
<iframe src="https://macaulaylibrary.org/asset/31723881/embed" height="504" width="640" frameborder="0" allowfullscreen></iframe>

#### The migration of the American golden plover according to Brad Harris (Jack Black) in *The Big Year*. 
<iframe width="560" height="315"
        src="https://www.youtube.com/embed/bxygINPm5zY?start=30"
        title="YouTube video player" frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
</iframe>

#### The migration patterns of the American golden plover according to the World of Birds (Cornell University).
<figure>
<img
src="https://cdn.download.ams.birds.cornell.edu/api/v1/asset/39445421/2400"
alt="`Distribution of the American Golden-Plover. Source: Birds of the World" />
<figcaption aria-hidden="true">Distribution of the American Golden-Plover, per Birds of the World. Source: <a
href="https://www.allaboutbirds.org/guide/American_Golden-Plover/overview">Birds of the World</a></figcaption>
</figure>

#### The migration patterns of the American golden plover according to GBIF observations.
**Note:** See the code that created this and a deeper explanation of the methods [here](https://natshoff.github.io/portfolioPosts/pluvialisDominica_portfolio.html)!
<embed type="text/html" src="maps/pluvialisDominica_migration.html" width="600" height="800">

#### How do these three sources for migration information on the American golden plover compare?
**Birds of the World and Brad:** We can see clearly that Brad Harris and Birds of the World are on the same page. The map shows that the American golden plover spends it's non-breeding overwintering time in northern Argentina, and migrates through both Guatemala and Illinois on it's way to breed in the tundra. 

**How does our map agree?** Our map broadly agrees! We see winter (Dec - Feb) plover observations concentrated in southern South America. Migrating birds reach the Tundra by May and don't leave until August. Their overflight takes them through Guatemala and Illinois. Notably, this timing agrees with other published timings of American golden plover migration. For example, a conservation plan by [Clay et al., 2010](https://whsrn.org/wp-content/uploads/2019/02/conservationplan_amgp_v1.1._2010.pdf) notes that plovers start migrating south from their breeding habitat in late June to mid-July (these are failed breeders), with the majority of the adults leaving in August. They also note that August is the first month where birds arrive on non-breeding grounds, which also agrees with our map. There is also agreement with literature on the birds northern migration. Clay et al state that birds start leaving non-breeding ground in late January, with most leaving in February. Some birds even stick around in South American until April and May, which our map also shows. April is major influx of birds in the Missouri, Mississippi, and Ohio River valleys. Plovers arrive on breeding grounds starting in mind-May to early June, which our maps clearly show. 

**How does our map disagree?** Our map is possibly overestimating the range of the American golden plover. You can see that the overwinter observations of the plover (see January) extend all the way to the southern tip of South America. It is certainly possible that some birds migrate this far south, but our map might be affected in part by the size of the ecoregions we're using to bin occurrences. For example, if a bird was spotten in the northern area of the one of the southern-Argentinian ecoregions, the entire ecoregion will be filled. The same pattern can be seen in the Artic tundra ecoregions. Finer spatial resolution binning could improve this.

**Something cool to note:** There is a small population of American golden plovers in Europe. While some of these might be misidentifications of European golden plovers (*Pluvialis apricaria*), we can observe a similar (albeit much small scale) version of the plover migration. Overwintering populations migrate to the northern Spain August - November, and spend the summer in the UK.



### Climate change in Chicago
![climate in chicago](img/chicago_maxtemp.png)

**Hot days in Chicago are getting hotter:** This simple linear regression for a weather station in Chicago, IL shows that daily maximum temperature is increasing at a rate of 0.04° C per year. Data source: [NCEI](https://www.ncdc.noaa.gov/cdo-web/datasets/GHCND/stations/GHCND:USC00111577/detail).
See the code [here](https://natshoff.github.io/portfolioPosts/climateAssignment_hofford.html)!

### Interactive Cahaba Map
<embed type="text/html" src="maps/cahaba.html" width="600" height="600">

**Cahaba River, AL:** The Cahaba River is the longest free-flowing river in Alabama and a part of the Mobile River basin (194 miles/ 312 km).

