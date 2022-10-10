Introduction:
Doctors Finder is a simple TYPO3 extension based on PHP, fluid , LESS, and Javascript, 
where we can add unlimited Doctors with unlimited Symptoms to heal, by simply assigning Symptoms to doctors in backend.

Installation :
- You need to have a  running TYPO3 CMS >= 11.5
- Upload doctors_finder extension via Extension Manager
- install Extension after Uploading
- include Extension doctors_finder in Website Template if exists, create a new Template in case there is no Template.
- if there is no page Object please Upload doctors Extension (site package) a basic TYPO3 site package extension.
- make sure to SQL dump to page UID 1, or just simply ALTER UID column in each SQL Table from 1 to whatever your wish.
- add frontend Plugin from list wizard and choose storage page where data sets are saved.
