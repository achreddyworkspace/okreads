### Task 1: Code Review

**bugs / changes :**
1. Search is not working properly. For example :
	- throws 500 internal server error, if we search with "JHKFJHKJHKJSHJFSFSFSF". `Should display some error message`
	- throws 422 Unprocessable Entity error, if we search with "#". `Should display some error message`
	- firstly, search with javascript and later search search with "#", it throws error backend but shows the old search data. `Should display some error message`
	
2. Limit the length of search text box

3. Responsive is not set properly

4. My Reading List is not in order. `Can make ascending order by book`

5. If I search with javascript, I shows 10 books, and I have added all. But If I want more what to do.? `Can add pagination for each search`

6. npm run test, failed one test case : `in reading-list.reducer.spec.ts file`

7. can show read color highlight if blank on click search button with message

8. Alt not exists for images

**suggestions:**
1. Add multiple filters for search. `Ex : search between date range, by author, famous, top sale, etc`

2. On click on image. Provide more info and zoom in the cover page, and provide suggestions, ratings.

3. On click on search, Show last searched data with remove on it.

4. min characters to search. `3 characcters minimum`

5. global scss file.

6. check performance using jmeter

7. Can possibly do penetration test, SAC test, SAST test before production

**improvements:**
1. performance can improved by using cache from search

2. project can be divided by micro-frontends.

3. update all packages to latest angular. Lot of dependencies were deprecated.

4. routing improvements, add validations, form controls, lazy loading.

5. apply security things like proxy.config, login / user based search.

6. instant search can be added.

7. can provide suggestions based on reading list.

8. no proper exception handler.

9. can separate constants instead of hard-coding