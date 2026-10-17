SOFI GITHUB - SETUP CHECKLIST
Note: Install the Github CLI

- Adding the SOFI Authentication Token to GitHub Action Secrets

gh secret set API_KEY --body "PASTE_TOKEN_HERE"

- Check if the SECRET was added.

gh secret list

OTHER FUNCTION/S

- If you want to delete a secret

gh secret delete SECRET_NAME
