# UiPath Job Search Robot

UiPath RPA robot that searches job listings (eJobs), collects the results in `Rezultate.xlsx`, summarizes them with a local LLM (Ollama, llama3 at `localhost:11434`), and sends the results by email.

Team: Sofronea Georgian, Alexandru Vasii, Denis Mitica, Popa Daniel, Preda Cristian.

## Setup

Open `Robot_Cautare_Job/project.json` in UiPath Studio. Before you run it, set your own email address and password (the `CHANGE_ME` / `your.email@example.com` placeholders in the workflows) and make sure Ollama is running locally with the llama3 model. The standalone `extra/Process.xaml` uses the Gemini API instead (config value `Gemini_ApiKey`).

`extra/` contains standalone versions of the workflows (`CautaJob.xaml`, `Process.xaml`, `TableDataScraping.xaml`).
