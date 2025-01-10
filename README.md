# photo-spotter-ai-service

## Table of Contents
- [Overview](#overview)
- [Planned Features](#planned-features)
- [Environment and Dependencies](#environment-and-dependencies)
- [API Endpoints](#api-endpoints)
- [Deployment and Usage](#deployment-and-usage)
- [Tasks](#tasks)

## Overview
This service delivers AI-driven recommendations and analysis, such as personalized shot suggestions, weather/light scoring, and possibly style analysis based on user preferences or location data.

## Planned Features
- Collaborative filtering or content-based recommendation algorithms
- Weather-based scoring (cloud coverage, golden hour intensity)
- Real-time recommendations for nearby photo opportunities
- Photo style analysis (optional)

## Environment and Dependencies
- Go or .NET 6+ for the main service
- Optional external AI libraries or a custom ML pipeline
- Docker for containerization

## API Endpoints
- `/ai/recommend` for spot suggestions based on user history
- `/ai/weather-score` to calculate photographic potential given weather data
- `/ai/style` for analyzing photo style (optional)

## Deployment and Usage
- Run locally using `dotnet run` or `go run main.go`
- Build Docker image: `docker build -t photo-spotter-ai-service .`
- Deploy to Kubernetes with a basic manifest or Helm chart

## Tasks
- Set up basic recommendation scaffolding
- Integrate weather data for light scoring
- Add test coverage in continuous integration
- Provide a `/health` endpoint
