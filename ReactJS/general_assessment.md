## General Technical Assessment - ReactJS
### Background

The pandemic, COVID-19, requires people to practice social distancing. Many are quarantined at home or at temporary facilities. In the light of the new social dynamics, people experience feelings of isolation which potentially have an impact on mental health. Therapy, once taboo, is starting to be acceptable in our society. However, there are a few problems therapists face while engaging with their clients during this period of isolation –
Clients may face several emotions between therapy sessions. These crucial data points are inaccessible, and available only from memory recall.
Therapists maintain notes and mind maps based on their interactions with clients.

As a simple solution for the clients and the therapist, build a Django Application for clients to maintain their emotions journal, and for therapists to view journals (authorised by clients) along with making their own notes and managing their schedule.

### User stories
A Client should be able to …
* Create a Client account and login using their email and password
* View list of therapists who have access to emotions journal along with these actions –
    * Remove a therapist mapped to account
    * Remove a therapist’s access to the journal, but not mapping to account
    * Send a message to a therapist and view the history of exchanges.
* Approve or reject a therapist’s request for access to Client emotions journal.
* Add record of an emotion felt. This should include the time of emotion, feeling and intensity (For vocabulary of emotions/feelings with intensity, refer [here](https://tomdrummond.com/app/uploads/2019/11/Emotion-Feelings.pdf))
* Request for an appointment in an available slot
* Select therapists from a list of available therapists on the platform

A Therapist should be able to …
* Create a Therapist account and login using their email and password
* View list of clients along with actions like –
    * Request client for journal access
    * Send a message to a client and view the history of exchanges.
    * Remove a client
* View client journals
* Create a new session (therapy appointment). Each session with –
    * Private notes, visible only to the therapist
    * Shared notes with the client. For any assignments.
* Modify details of each session