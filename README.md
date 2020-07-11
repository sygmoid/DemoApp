# Template for static GitHub hosted flask applications

Build and host a static version of your flask application on GitHub Pages.

## Usage

- Click on [Use this template](https://github.com/soerface/template-flask-bootstrap/generate)
- Make a commit to trigger a new build

### Optional: Use your own domain

- Open `.github/workflows/deploy.yml`
- Uncomment the `CNAME` environment variable, using your custom domain as value
- Make a commit to trigger a new build
- Properly configure your domains DNS settings
    - If you want to use a subdomain, set a `CNAME` entry pointing to `<user>.github.io`
    - If you want to use an apex domain, set an `A` record, pointing to the [IP addresses from GitHub](https://help.github.com/en/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site#configuring-an-apex-domain)
   
Changing DNS entries may take a while. After a couple of minutes, maybe an hour, try taking a look at your site!