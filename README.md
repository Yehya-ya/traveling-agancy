📄 Job Description From Client

I usually advise reading the job description three times, with different goals in mind:

- Reading 1: just get familiar with the overall idea of what the project is about

- Reading 2: try to come up with DB structure - list the tables and their relationships (luckily, in this case, the client did it for us)

- Reading 3: try to come up with a plan of action, re-arranging the list of tasks from the client to the order in which things would be actually built

Along the way, another result of this should be the list of questions for the client. If you don't ask them right away, you may suffer from "unpleasant surprises" or misunderstandings in the future, leading to many painful code changes.

With those goals in mind, here's the full job description from the client.

You can also read it in a separate Google Docs format here if you prefer.

📄 Frist Requirements

- multigard (admin - users)

- admin

- crud for travels

- crud for tours

- client

- list of travels

- list of tours by slug with filter

tables:

- admin:id, name, email, phone, email, password, remember_token, updated_at, created_at

- user:id, name, email, phone, email, email_verified_at, password, remember_token, updated_at, created_at

- travel: id, name, description, slug, thumbnail, number_of_days, updated_at, created_at

- tour: id, name, start_at, end_at, price, updated_at, created_at
