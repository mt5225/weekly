# 流水帐

1. do translation about 600 words for uDCV product library. then library is re-compiled to fill the e2e process for uDCV.
2. confirm with teams about the **standard process** for e2e, result as following:
 - for scene building, online or standalone uDCB. <br> 
 - note the **visio drawing path is deprecated** and no longer support. i also talk to the developer *xiaopan* , he said the visio plugin is not under active developing, and in order to compatible with English version of uDCV, it needs to do the translation and modify the export function, which, involves lots of work. while at the long term, visio is out.
 - also talk to *wangtao* about the EMC Singapore project, he said for the time being a large part of implementation is done by visio not online uDCB. need to clearfy within week. 
 - about standalone uDCB, *lijian* will finish the license process and create an release within next week.
 
3. e2e process testing, until Thursday, the export scene from uDCB still need minor modification to work with uDCV. uDCB team is outing at Friday, so i make sure it be done early next week.
4. Regarding English website, i am working on so call the *dynamic* part: user and scenes management [USM].
 - existting uinnova.com USM functions: *deprecated*, reason: not compatible with new version of uDCB, not suitable for new English web site, and maintenance personnel is reluctant to make modification and improvements.
 - leverage **NodeBB** as base of USM. i have wrote the plugin widget to show uDCB link for registered users. [nodebb-plugin-mt5225_001](https://www.npmjs.com/package/nodebb-plugin-mt5225_001), for installation, type <br>
 ``` npm install nodebb-plugin-mt5225_001 ```<br>
 under nodebb install directory.

 - store screen capture image to AWS S3,  [details](https://github.com/mt5225/uDCB-srv)
 - will finish (basical) USM function early next week.
 