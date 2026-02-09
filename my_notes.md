## env vars 
export PY_SERVICE_URL=http://localhost:8000
printenv

## entry point 
netlify dev 

(this runs but doesn't show console logs...)
(and it messes up the URL, so it doesn't work with the generate eflint endpoint)
npm run dev


## Had to run the generate-eflint on WSL 
uvicorn service.app:app --reload --host 0.0.0.0 --port 8000