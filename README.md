# Data Roles

This vocabulary lists the roles that Agents - People and Organisations - play in relation to data. This is an extended and Semantic Web version of the International Organisation for Standardization's [ISO19115-1 standard](https://www.iso.org/standard/53798.html)'s Role Codes codelist.

This vocabulary is online at **<https://linked.data.gov.au/def/data-roles>**.

## License
The contents of this repository are licensed under Creative Commons 4.0 International. See the [LICENSE deed](LICENSE) in this repository for details.

**NOTE:** that the original code list from which this content is derived is &copy; International Organization for Standardization.

## Contacts
Contributor:  
**Nicholas J. Car**  
*Adjunct Senior Lecturer*  
Australian National University  
<nicholas.car@anu.edu.au>  

## Technical details

This vocabulary is delivered online as a website comprising RDF & HTML built from source files in this repository by the [Jekyll](https://jekyllrb.com) static site generator files and served by [GitHub Pages](https://pages.github.com/) at <https://agldwg.github.io/data-roles/>. The [AGLDWG's PID System](https://www.linked.data.gov.au/) provides a web address redirect service to make the quoted persistent URLs in the vocabulary resolve to this website. 

The only vocabulary sources files that need editing directly are `rdf/_vocabulary.ttl` `and md/index.md`. All other files are auto-build by the Python scripts (see bwlow). 

### Jekyll Commands
Launch new site

jekyll new . --force


Serve locally

bundle exec jekyll serve

to fix dependencies: bundle update && bundle install


### Python scripts

Several scripts are used to generate the HTML/markdown files from RDF. See `_scripts`.