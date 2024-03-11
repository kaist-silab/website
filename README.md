<h1 align="center">KAIST SILAB</h1>

> [!NOTE]  
> This website is actually not being used at the moment. Please refer to the [official website](http://silab.kaist.ac.kr/) for the most recent information!

## Previewing (locally)
1. Install Docker Desktop (recommended) or just Docker and start it.
2. Run `./.docker/run.sh`.
3. Wait for Docker to build a sandbox with all the languages and packages the template needs. Should take ~2 min the first time and be almost instant on subsequent runs.
4. Wait for Docker to start the preview. You should shortly get a localhost link that you can open in your browser to see your site preview.
5. When you make a change to a file in your repo folder, your preview should refresh/update automatically, except for changes to _config.yaml which require you to manually refresh.
6. When you make a change to your sources or metasources, the cite process should automatically re-run, and when finished be reflected in your preview via the same behavior as above

Other ways to preview [here](https://greene-lab.gitbook.io/lab-website-template-docs/getting-started/preview-your-site#on-your-computer-locally)

## Deploying

We deploy with the [Jekyll action](https://github.com/kaist-silab/website/blob/main/.github/workflows/jekyll.yml) as recommended by Github


[**Documentation**](https://greene-lab.gitbook.io/lab-website-template-docs)

Made with [lab-website-template](https://github.com/greenelab/lab-website-template)
