# Hi there :octocat:

I am a PhD candidate in Sociology currently in the final stage of my doctoral studies.
My research focuses on social inequalities with a particular emphasis on care work and its intersections with paid work trajectories.

I am also committed to developing skills in quantitative methods and data analysis, continuously learning and applying these tools in my work.

![](https://private-user-images.githubusercontent.com/70701842/480198956-e8978313-2c2e-4e24-8f48-e19c4021df79.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NTU3Mjg2MzIsIm5iZiI6MTc1NTcyODMzMiwicGF0aCI6Ii83MDcwMTg0Mi80ODAxOTg5NTYtZTg5NzgzMTMtMmMyZS00ZTI0LThmNDgtZTE5YzQwMjFkZjc5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNTA4MjAlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjUwODIwVDIyMTg1MlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTFiMzllZjQ4YWY2MDc2YzNmNTgzNTJlZWQwNWQxMDg4ZjZkNjZiNTM0MzE2YjExZDJhMGYzYzZhNDMxMzgyMTkmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.Hr3IOig13B4GRlcdw_bxG6ffUsQiu384D0GFf_yS_o8)

## Deployment

The repository includes a GitHub Actions workflow in `.github/workflows/pages.yml` that uploads the pre-rendered `docs/` folder to GitHub Pages whenever you push changes to the `main` branch. To finish enabling the deployment:

1. Open **Settings → Pages** in the repository.
2. Choose **GitHub Actions** as the publishing source.
3. Wait for the "Deploy site to GitHub Pages" workflow to complete successfully under **Actions**.

Once that workflow finishes, the static files in `docs/` will be served through GitHub Pages. You can monitor the exact URL from the workflow summary—GitHub will print the published address in the deployment step.

### Expected site URL

- If the site lives in a repository named `vgonzalezm.github.io`, GitHub serves it directly at `https://vgonzalezm.github.io/`.
- If you keep the Quarto source in another repository (such as this one), the published address follows the pattern `https://<tu-usuario>.github.io/<nombre-del-repo>/` (por ejemplo, `https://vgonzalezm.github.io/vsgonzalezm/`).

After the first deployment, visiting the appropriate URL should show the same pages that appear under `docs/`. If you still encounter a 404 error, confirm that the GitHub Actions run succeeded and that the chosen repository matches the expected domain.
