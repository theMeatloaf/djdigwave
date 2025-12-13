to start local server:
cd public_html && python3 -m http.server 8000

to End local Server:
lsof -ti:8000 | xargs kill


to upload:
scp -r public_html/* username@your-domain.com:~/public_html/