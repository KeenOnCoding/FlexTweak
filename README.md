# FlexTweak
 ### CLIENT<br />
 ng build --configuration production --aot<br />
 firebase deploy<br />
 ### SERVER<br />
 gcloud auth login<br />
 gcloud functions deploy csharp-http-function --gen2 --entry-point=FlexTweak.Function.GoogleCLoud.Function --runtime=dotnet6 --region=us-west1 --source=. --trigger-http --allow-unauthenticated<br />
