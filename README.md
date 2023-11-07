# Rails, Kamal, Vector, and Honeybadger

This is a sample application to demonstrate how you can integrate Honeybadger
Insights into your Rails application using Vector.

## Requirements

1. A server to deploy your application.

2. A container registry.

## Instructions

1. Clone the repo.

2. Edit the `config/deploy.yml` with your server IP address and container
registry account.

3. Install the kamal gem.

```
gem install kamal
```

4. Setup and deploy the application.

```
kamal deploy
```
