#!/usr/bin/env groovy

def lvProjectPath = "source\\Test Sandbox.lvproj"
def lvBuildSpecName = "myBuildSpec"
def lvVersion = "20.0"
def lvBitness = "32"

lvPipeline(lvProjectPath, lvBuildSpecName, lvVersion, lvBitness)
