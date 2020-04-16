Journal for April 8th, 2020

# What I learned today 

Manuscript Images on my timeline 
    - The only way to include images in your timeline is to find the file on the web. 
        ^ which is done by typing the web address of the file into the "media" column of the spreadsheet

IIIF Images 
    - Images are available through the web 
        IIIF = International Image Interoperability Framework" 
    - People can do more than point to them with this standard 
    - You can do this by following the protocols of the API. 
        API = Application Programming Interface
    - Example: Being able to talk to each other on Google (docs, slides, etc.) 

Download Walden Image 
    2 Url's are different in size causing the image to load faster 

URL Types: 
Template {scheme}://{server}{/prefix}/{identifier}/{region}/{soze}/{rotation}/{quality}.{format}
- {scheme} = https 
- {server} = cdm16003.contentdm.oclc.org
- {/prefix} = /digital/IIIF
- {region} = full 
- {size} = full (first URL) or pct:10 (second URL)
- {rotation} = 0
- {quality} = default
- {format} = jpg

Most Important Parts of URL: 
- region - size - rotation 

https://cdm16003.contentdm.oclc.org/digital/iiif/p16003coll16/8/full/pct:10/0/default.jpg