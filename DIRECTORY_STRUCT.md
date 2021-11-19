# Some references on directory structures and our choice for this project

## Some web resources (among many)

https://intro2r.com/dir-struct.html

https://martinctc.github.io/blog/rstudio-projects-and-working-directories-a-beginner's-guide/

https://www.r-bloggers.com/2018/08/structuring-r-projects/

https://aosmith.rbind.io/2018/10/29/an-example-directory-structure/


## Our plan
.
└── project

    ├── src            - folder containing script files or function files
    
    ├── rmd       - folder containing .Rmd files where we conduct analysis.  USE GOOD NAMES 
    
    ├── output         - folder html, pdf, or ppt output reports 
    
    │   ├── plots      - folder plots to be kept that could be use in publications or reports
    
    ├── data
    
    │   ├── raw        - folder for untouched, raw data
    
    │   └── processed  - folder for data after we have done some processing
    
    ├── README.md
    
    └── .gitignore


