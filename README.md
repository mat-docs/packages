# Mclaren Applied Nuget Repository

Nuget package repository for Mclaren Applied, a valid license is required to use these libraries. If you need a license, please speak to [MA customer support](https://mclarenappliedtechnologies.zendesk.com/hc/en-us/categories/360000363854-ATLAS-and-SQLRace).

## Steps to connect from Visual Studio

1. Sign up to GitHub and create an account.
2. Follow the steps [here](https://docs.github.com/en/github/authenticating-to-github/creating-a-personal-access-token) and generate your own PAT token. _Ensure the PAT token has the read:packages scope._

![image](https://user-images.githubusercontent.com/71443454/114562252-3d102e80-9c66-11eb-9774-3b93ea551a0d.png)

3. Add the feed `https://nuget.pkg.github.com/mat-docs/index.json` to Visual Studio.

![image](https://user-images.githubusercontent.com/71443454/114560865-fa018b80-9c64-11eb-80bd-0d9e9f42bb79.png)

4. When prompted for credentials, enter your GitHub username and PAT token generated from above.

![image](https://user-images.githubusercontent.com/71443454/114561355-68464e00-9c65-11eb-8125-30be5ff038c9.png)

On Windows machines, the credentials are stored within Credential Manager. If you encounter problems authenticating and need Visual Studio to re-authenticate using different credentials, the saved entry can be removed from:

![image](https://user-images.githubusercontent.com/71443454/115026664-ad16f280-9eba-11eb-96ab-9d41004c645f.png)

## Notes for users currently using Bintray

The current Bintray repository will be switched off on 01-May-2021. If you have previously used Bintray to add packages to your project, you don't need to add them again from this repository, they will continue to work as expected. However, it is strongly advised to switch to the new repository now so you can receive future updates to packages when they are released.


