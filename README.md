
# CompoundDb.Hsapiens.HMDB.5.0

We made this SQLite database to carry out analysis for a publication work.

A more explained resource can be found at [MetaboAnnotationTutorials] (https://github.com/jorainer/MetaboAnnotationTutorials/) along 
with SQLite file.

This package was developed by using [CompoundDb](https://github.com/rformassspectrometry/CompoundDb) to use with 
[MetaboAnnotation](https://github.com/rformassspectrometry/MetaboAnnotation) to carry out compound annotation  based on 
[HMDB](http://www.hmdb.ca) version 5. 



The metabolite structure file (in SDF format) structures.zip and hmdb_experimental_msms_spectra.zip were used to develop the package 
by using the functions of the package [CompoundDb](https://github.com/rformassspectrometry/CompoundDb).

Data from HMDB was downloaded on: 20/June/2022.


If you find it useful please cite:  [CompoundDb](https://github.com/rformassspectrometry/CompoundDb), [HMDB](http://www.hmdb.ca) and other above-mentioned  packages.

Note: note because of LFS, normal installation like install_github() or remotes::install_github() might through error


----
## Best way to install ## 

1. Clone CompDb.Hsapiens.HMDB.5.0 git.
``git clone https://github.com/AnupamGautam/CompDb.Hsapiens.HMDB.5.0.git ``

2. Build CompDb.Hsapiens.HMDB.5.0 
``R CMD build CompDb.Hsapiens.HMDB.5.0 ``

wil create CompDb.Hsapiens.HMDB.5.0_0.0.1.tar.gz

3. Install CompDb.Hsapiens.HMDB.5.0_0.0.1.tar.gz 
``R CMD INSTALL CompDb.Hsapiens.HMDB.5.0_0.0.1.tar.gz ``

You can also specify the library path in the above command (with -l ), if want the package to install in a specific directory  
``R CMD INSTALL -l /PathToFolder/ CompDb.Hsapiens.HMDB.5.0_0.0.1.tar.gz `` 
