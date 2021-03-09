# Guide on adding a new publication to the website 

1. Add the metadata of the publication as a new entry in the `pages/publications.md` file. 

    Example: 

    ```
      - title: "A Toolbox for Realtime Timeseries Anomaly Detection"
        authors: Markus Bobel, Ilias Gerostathopoulos, Tomas Bures
        venue: "IEEE International Conference on Software Architecture (ICSA 2020), to appear."
        doi: https://ieeexplore.ieee.org/document/9095724
        pdf: 2021-ICSA-IG-anomaly_detection_tool.pdf
        year: 2020
        type: conferences
    ```
    Notes: 
    * `title` should be always given in double quotes
    * `venue` should be always given in double quotes
    * You can leave both the `pdf` and the `pdf` empty if you prefer.  
    * As `type`, you can use `conferences`,`journals`,`workshopsSpecialTracks`,`bookChapters`

2. (optional, only if you want to add a pre/post print) Add a PDF file to the `pubs` folder. 
    The name of the PDF has to match the name you specified in the metadata entry (e.g. `2021-ICSA-IG-anomaly_detection_tool.pdf`) 

    As a suggestion, we can use the following pattern: \
    `<year>-<venue>-<group member initials>-<anything else>.pdf`


