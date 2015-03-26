
django-meta-m2m
==================

WORK IN PROGRESS

Relate anything to anything, with meta data. 


What it Does
------------

The purpose of this project is to allow you to create database-level relationships between various objects with meta data
about the relationships, using a consistent API. 

This app is based on [django-generic-m2m](https://github.com/coleifer/django-generic-m2m), but adds the ability to uses 
the Postgres HStore field to store meta data about the relationship between the two attached objects. Meta data to be
collected about the relationship can be specified as a Django form object, allowing for easy validation and rendering of 
the form.
