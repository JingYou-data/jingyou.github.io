---
layout: post
title: "Building My First Data Pipeline: Weather API Integration"
date: 2024-12-16
categories: data-engineering projects
tags: python api docker etl
---

# Building My First Data Pipeline

## Project Overview

Two months into my data engineering journey, I successfully built a multi-source ETL pipeline that integrates real-time weather data with PostgreSQL database information.

**Project:** Weather Data Integration Pipeline  
**Tech Stack:** Python, Pandas, PostgreSQL, DuckDB, Docker  
**Timeline:** 1 week  
**Status:** Completed ✅

---

## The Challenge

The goal was to build a data pipeline that:
1. Fetches real-time weather data from OpenWeatherMap API
2. Extracts weather station information from PostgreSQL
3. Merges the data using Pandas
4. Validates data quality with DuckDB
5. Stores optimized results in Parquet format

---

## Technical Architecture

### Data Flow
