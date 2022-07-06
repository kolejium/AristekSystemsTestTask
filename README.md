# AristekSystemsTestTask

Create a simple Angular app that displays a UI for searching books using the following requirements:
1.	Create a simple .net 5+ or NestJS HTTP REST or GraphQL API that does the following:
	1.	The endpoint should accept search terms as supported by the Google Books API.
	2.	On a GET, the endpoint should search its own datastore for results. If it does not find any, it should use the Google Books API to populate its own datastore and return results to the client. If it does find results, it should return those to the client.
	3.	Create unit tests.
2.	The UI should allow for a search term and a sort by author or alphabetically.
3.	The app should use the following:
	1.	SCSS, and
	2.	Angular Material.
4.	As a bonus, you can also use the following:
	1.	Nrwl/nx (https://nrwl.io/) to organise the project, and 
	2.	ELF for state management (Elf | A Reactive Store with Magical Powers (ngneat.github.io)).
