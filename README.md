# FragmentStack [![NuGet Badge](https://buildstats.info/nuget/Xamarin.FragmentStack)](https://www.nuget.org/packages/Xamarin.FragmentStack/) 

Port of https://github.com/abhishesh-srivastava/fragstack to Xamarin.

## How to use

Have a look at [README.md](https://github.com/abhishesh-srivastava/fragstack/blob/master/README.md)

## How to install

### Android

Add [Xamarin.FragmentStack](https://www.nuget.org/packages/Xamarin.FragmentStack)

        PM> Install-Package Xamarin.FragmentStack -Version 1.0.0

## How to build

    msbuild Xamarin.FragmentStack.sln /t:Xamarin.FragmentStack /p:Configuration="Release" /p:BuildProjectReferences=false

## How to publish nupkg

E.g.: to [https://www.nuget.org/](https://www.nuget.org/) using [myApiKey](https://www.nuget.org/account/apikeys)

    nuget push Xamarin.FragmentStack/bin/Release/*.nupkg -Source https://api.nuget.org/v3/index.json -ApiKey myApiKey

## Contributors

[Jan Rabe](jan.rabe@kibotu.net)

### License
<pre>
Copyright 2018 Jan Rabe

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
</pre>
