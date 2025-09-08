# Chat CXone Demo

This is a demo website integrating **CXone Chat** using Google Tag Manager or direct script embedding.  
The site is hosted on GitHub Pages and demonstrates a basic chat flow with department selection, REST API lookup, and agent routing.

---

## Features

- **Initial customer info collection**: Name, Email, Phone, Department (Customer Service / Tech Support)  
- **Hours of operation check**: 6am–9pm EST, with an automatic message if outside hours  
- **REST API integration**: fetches customer address and company information to display to agents  
- **Agent routing**: routes chat to the correct skill based on department  
- **Queued messages**: automated messages while the customer waits for an agent  
- **Timeout**: ends interaction if customer does not reply within 60 seconds  
- **Custom HTML button** to open the chat on your website  

---

## How to Use

1. Open the site on a browser (hosted via GitHub Pages).  
2. Click the **"Open Chat"** button.  
3. The CXone chat widget will open and follow the configured Studio flow.  

---

## Deployment on GitHub Pages

1. Ensure `index.html` is in the root of the repository.  
2. Go to **Settings → Pages** → set **Source** to `main` branch and folder `/root`.  
3. Save and wait a few minutes for GitHub Pages to deploy.  
4. Access your site at:  
