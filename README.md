# How to run a decentralized version of Fiat UI for free (in < 5 minutes)

Below, I'll walk you through how to run your own Fiat UI for free.

Prerequisites:
1. GitHub account
2. Git installed on your machine

Instructions:
1. (Create a free Alchemy account)[https://www.alchemy.com/]
2. Create an Alchemy project on either Mainnet (for production) or Goerli (for testing)
3. Fork the [Fiat UI GitHub repo](https://github.com/fiatdao/fiat-ui.git)
4. Create a free Fleek account (using your GitHub login)
5. Create a new Fleek site
6. Connect Fleek to your forked version of the Fiat UI repo:
![image](https://user-images.githubusercontent.com/101981457/182909143-72860a47-a729-4f7b-b698-b82ddf791b76.png)
7. Select "IPFS" Hosting Services
8. Select "NextJS" as the framework:
![image](https://user-images.githubusercontent.com/101981457/182909327-73dee41d-f488-4e47-ab85-7a58a36b718e.png)
9. Open the "Advanced Section" and plug in the following environments variables using the secrets for your newly created Alchemy account:
![image](https://user-images.githubusercontent.com/101981457/182909706-0278e0a1-eb84-4988-b112-3a55f74469d4.png)
10. Click "Deploy Site"!
