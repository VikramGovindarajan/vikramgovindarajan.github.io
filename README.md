
# Information

1. Upload any files (like PDFs, .zip files, etc.) to the `files/` directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.
1. (Optional) To generate your resume PDF from LaTeX, use the provided `Makefile` inside the `resume/` directory. Run `make` inside `resume/`, and it will generate `resume.pdf` in the same directory ans will be linked.
   
   
## Running Locally

When you are initially working your website, it is very useful to be able to preview the changes locally before pushing them to GitHub. To work locally you will need to:

1. Make sure you have ruby-dev, bundler, and nodejs installed:  
   ```sh
   sudo apt install ruby-dev ruby-bundler nodejs
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `jekyll serve -l -H localhost` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

If you are running on Linux it may be necessary to install some additional dependencies prior to being able to run locally: `sudo apt install build-essential gcc make`
