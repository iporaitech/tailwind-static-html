# tailwind-static-html

Template repo with simple boilerplate to create static html website styled with TailwindCSS

It's built with Webpack and styled with TailwindCSS. See webpack.\* files for bundling info.

Scripts

Start development server with yarn dev [--watch]

Build for production with yarn build:prod

Deploy

Delete all files from www.iporaitech.com S3 bucket
yarn build:prod and copy newly generated production files from dist to the S3 bucket
Invalidate cache in CloudFront using
/\*
/en/\*
