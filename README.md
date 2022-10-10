Introduction:
Doctors Finder is a simple TYPO3 extension based on PHP, fluid , LESS, and Javascript, 
where we can add unlimited Doctors with unlimited Symptoms to heal, by simply assigning Symptoms to doctors in backend.

Installation :
- You need to have a  running TYPO3 CMS >= 11.5
- Upload doctors_finder extension via Extension Manager
- install Extension after Uploading
- include Extension doctors_finder in Website Template if exists, create a new Template in case there is no Template.
- if there is no page Object please Upload doctors Extension (site package) a basic TYPO3 site package extension.
- when you import SQL files to database make sure to import it to page with uid = 1 or you can alter uid column to another page uid, or you can create data sets new.
- create a simple page as Homepage or subpage.
- add frontend Plugin from list wizard and choose storage page where data sets are saved.
