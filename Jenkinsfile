#!/bin/groovy

node ('testslave') {
		stage ('Build') {
			checkout scm
			stash ('original-repo') // Save original state of all files for later use on other nodes
    }
}   
