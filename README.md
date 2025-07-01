# API-Testing-with-AI-via-Keploy-

Use Keploy for API Testing (AI-Based)
🧪 Steps:
Install Keploy CLI


curl -s https://raw.githubusercontent.com/keploy/keploy/main/install.sh | bash
Run Keploy in record mode

keploy record --proxy-port 8081 --app-port 5000 --test-path keploy-tests
Use your API via curl or Postman — this will generate test cases based on your OpenAPI schema.

Run Keploy Tests

keploy test --proxy-port 8081 --app-port 5000 --test-path keploy-tests
View Reports on the Keploy Dashboard

You can sign in and view test coverage, latency, etc.

