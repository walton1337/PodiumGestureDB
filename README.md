# PodiumGestureDB
Gesture database for the Podium Kinect Application

This repository contains the open source component of Team ReKinect's senior capstone project. The database contains five gestures that are deemed negative interviewing habits. The gestures included are leaning, arm crossing, head tilting, pointing and touching face.

To use the database, within the gesture detector file of your Kinect WPF application, you can set the database path to:
private readonly string gestureDatabase = @"Database\ReKinectV1.gbd"

The remaining files are dependency files containing necessary data to detect the various gestures outlined in the database.
