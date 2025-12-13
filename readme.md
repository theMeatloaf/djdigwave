to start local server:
cd public_html && python3 -m http.server 8000

to End local Server if needed:
lsof -ti:8000 | xargs kill


to upload:
scp -P21098 -r public_html/*  username@djdigwave.com:~/public_html/