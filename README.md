# LiveData Android Example
Working With LiveData 

In this blog I will tell you about LiveData we focus basically below things
- What is LiveData
- Why should use livedata
- When should use 

## What is LiveData
LiveData is an observable data holder class. It observe LiveData objects for changes.

Basically, LiveData is an observable data holder. It lets the components in your app, usually the UI, observe LiveData objects for changes. LiveData is lifecycle-aware, meaning it respects the lifecycle of other app components, such as activities, fragments, or services

## Why should use livedata

References Article - https://androidwave.com/working-with-livedata/

In other words LiveData as a mix between Interface Listeners and the Event-Based solution, taking the good from each solution. As a rule of thumb, I would advise to use (or switch to) LiveData almost in every situation in which these other alternatives are considered (or were already used), and specifically, in every scenario in which we want to update the UI based on data changes in a clean, robust and reasonable manner.
