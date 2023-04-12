# About Us

![](https://making.close.com/static/close-collage-98741b61e25ef69b5e8d4d5129c839c2.jpg)

At [Close](https://close.com/), we're building the sales communication platform of the future. With our roots as the very first sales CRM to include built-in calling, we're leading the industry toward eliminating manual processes and helping companies to close more deals (faster). Since our founding in 2013, we've grown to become a profitable, 100% globally distributed team of 50+ high-performing, happy people that are dedicated to building a product our customers love.

## Our Tech Stack

### Backend

Our backend tech stack currently consists of Python Flask web apps with our [TaskTiger](https://github.com/closeio/tasktiger) scheduler handling many of the backend asynchronous task processing chores. Our data stores include MongoDB, Postgres, Elasticsearch, and Redis. The underlying infrastructure runs on AWS using a combination of managed services like EKS, MSK, RDS and ElasticCache and non-managed services running on EC2 instances. All of our compute runs through CI/CD pipelines that build Docker images, run automated tests and deploy to our Kubernetes clusters. 

Our backend primarily serves a well-documented [public API](https://developer.close.com/) and GraphQL endpoint that our front-end JavaScript app consumes. Our infrastructure is heavily automated using AWS tools, Terraform, and Ansible.

### Frontend

Our app’s frontend is a single-page JavaScript web app mostly written in React (originally built with Backbone.js) and built on top of our REST API & GraphQL endpoints. We bundle with Webpack and target only modern browsers. We test with Jest and React Testing Library. Our UI updates in near real-time and is written in LESS/CSS (with flexbox and grid layout) using CSS modules and takes advantage of fun technologies like Websockets and WebRTC. 

We care about performance (e.g. route-based code splitting), maintainability, and testability of our frontend code. We sweat the UI/UX details and work collaboratively with the Product team throughout the design process. This means diving into lo-fi Freehand wireframes, and communicating continuously when those ideas are brought to life using Figma and code.

# More about us

- [The Making of Close](https://making.close.com/) – Our behind-the-scenes Product & Engineering blog
- [Jobs at Close](https://jobs.lever.co/close.io/) – We're hiring for our 100% remote team
- [About Us](https://close.com/about) – Learn about us
- [API](https://developer.close.com/) – Our REST API for developers wanting to integrate with Close
