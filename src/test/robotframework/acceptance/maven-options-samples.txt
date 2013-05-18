*** Settings ***
Documentation   Test using only Robot Framework Collections Library
Library         BuiltIn

*** Test Cases ***
Log Robot Variable Defined In Pom Configuration
    [Tags]  configured-robot-variable
    Log     ${ROBOT_VARIABLE}