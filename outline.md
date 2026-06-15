Job:
    - title
    - location
    - job type
    - description
    - published at
    - vacancy
    - category
    - salary
    - experience

        - apply to
        - post

Blog
    - title
    - content
    - created at
    - category
    - tags
    - author

        - search
        - comment
        - recent post

contact
home

login

Relations:
	One to Many 	(author - post) ForeignKey
	Many to Many 	(user - groups)
	One to One 		(user - profile