@@ -1,5 +1,4 @@
// const express = require('express')// method-1
import connectDB from "./config/database.js";
import userRoute from "./routes/userRoute.js";
@@ -1,6 +1,4 @@
# See https://help.github.com/articles/ignoring-files/ for more about ignoring files.
# dependencies
 # dependencies
/node_modules
/.pnp
.pnp.jsimport express from "express"; // method-2
import express from "express";
import dotenv from "dotenv"; 
