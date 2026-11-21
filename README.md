# UiPath Job Search Robot

UiPath RPA robot that searches job listings (eJobs), collects the results in `Rezultate.xlsx`, can summarize them with the Gemini API, and sends the results by email.

Team: Sofronea Georgian, Alexandru Vasii, Denis Mitica, Popa Daniel, Preda Cristian.

## Setup

Open `Robot_Cautare_Job/project.json` in UiPath Studio. Before you run it, set your own email address and password (the `CHANGE_ME` / `your.email@example.com` placeholders in the workflows) and the `Gemini_ApiKey` config value.

`extra/` contains standalone versions of the workflows (`CautaJob.xaml`, `Process.xaml`, `TableDataScraping.xaml`).
