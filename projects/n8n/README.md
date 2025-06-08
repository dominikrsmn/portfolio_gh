go [back](../../README.md)

# n8n workflows

## Concept for pushup.vision's chatbots

![Anfragenworkflow](images/anfragenworkflow.png)

## E-Mail Tracking

Track E-Mails being opened once/multiple times

![E-Mail Sender](images/emailsender.png)
*E-Mails get sent with a 1x1px image src and it's database id*

![E-Mail Tracker](images/emailtracker.png)
*On GET request to the image src (which is a n8n webhook with the id as parameter), the email gets searched and set to opened/opened multiple times

## RAG AI-Agent

First version of pushup's chatbot in a single workflow

![RAG AI](images/rag.png)

## Lead generation and enrichment

Find company leads & owner's contact data in germany with a single keyword

![Scraper](images/scraper.png)
*scraping data off Google Maps*

![Scraper](images/enrich.png)
*enrich data by finding out contact data*
