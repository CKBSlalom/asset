# Custom Links Component


## Contact

- Christian Kildal-Brandt (christian.kb@slalom.com)


## Components

- Apex Classes: 
     - CPQ_CustomLinks
     - CPQ_CustomLinksTest
     
- LWC:
     - CPQ_CustomLinksComponent

- Custom Objects
    - Custom_Links_Header__mdt
    - Custom_Links_Item__mdt

## How It Works

The asset allows for the configuration of custom link components that can be utilized on various pages, such as the home page or a specific object's page. These links can perform a variety of functions, from directing to an external website to launching a complex screen flow. Additionally, the asset leverages both record and object context, enabling users to populate URLs with complex information that can create or edit records with a simple click. At Avis, we extensively utilized this feature to launch flows.

The asset employs custom metadata to store all this information and can be easily configured by an administrator without any prerequisite knowledge of coding.

### How to Use It

1. Create a metadata header record to organize link groups
2. Create metadata link records and attach them to specific header (Note: one can set object context through the object field and record context by placing {recordId} where the record id would be in the link)
3. Place the LWC on a given page and use the metadata header api name to choose of group of links
4. Test that the links work as expected
