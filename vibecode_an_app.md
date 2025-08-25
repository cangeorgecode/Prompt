I want to build a grammar checker + paraphrasing tool with django as the backend. I need all the code necessary to bring this project to life, including the packages I need to install, models.py, views.py, utils.py, all HTML templates. Assume I already have a django project, "proj" and an app, "app", set up.
 
Here are some of the features I need:-
- IP-based rate limits. Each free user can freely use the grammar checker and it will tell them if their grammar is correct. It will also return a better written version but this is only limited to 5 times per day. I think I will use django-ratelimit for this and django-redis.
- Users can upgrade ($15/month or $99 lifetime access) for unlimited conversion
I am using django-allauth for user authentication.
Use Stripe for payment
- I will need a full landing page, with the above pricings and include some longtail keywords such as:- "grammar check", "grammar checker", "grammar check online", grammar corrector", rewrite this sentence"
- Use a base.html and extend all HTML templates from it
- I also have an account/base_account.html for user authentication-related templates
- Include on-page SEO, and technical SEO (robots.txt and sitemap.xml and any other files needed), mobile-first approach.
- I am going to do programmatic SEO and need a simple blog system.
- Use HTMX for async functions and minimise javascript use.

 
In your response, gimme the full, completed code for each component of the project. You don't need to explain what the code does.
