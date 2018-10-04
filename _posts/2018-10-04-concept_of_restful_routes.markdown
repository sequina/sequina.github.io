---
layout: post
title:      "Concept of Restful Routes"
date:       2018-10-04 13:39:28 +0000
permalink:  concept_of_restful_routes
---


When learning about resetful routes I kept getting them mixed up with CRUD. It is important to understand that ROUTES and CRUD are different but they work together.

RESTful routes allow us to have a URL mapping from verbs such as, get, post, delete, and patch to our controller that hold the actions such as, create, read, update, delete.

Restful routes give us a consistent and easier way to manipulate data, and keep our routes organized.

I have to admit when leanring these routes I got the verbs mixed up with the actions. Below I have a chart that helped me remind myself what route I was working on and the action.


Action	                                                     HTTP Method
  INDEX	                                                           GET
  SHOW	                                                          GET
  CREATE	                                                       POST
  NEW	                                                              GET
  EDIT	                                                              GET
  UPDATE	                                                       PUT
  DESTROY	                                                     DELETE
