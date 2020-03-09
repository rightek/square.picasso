# Rightek.Square.Picasso
 Xamarin Android binding for [Square Picasso](https://github.com/square/picasso) (A powerful image downloading and caching library for Android)
 
This project is based on [this repo](https://github.com/mattleibow/square-bindings), we use `Picasso` in our projects, so we'll keep this repo up to date with [original (_java_) repo](https://github.com/square/picasso). _current version `2.71828`_
 
## Usage
```cs
Picasso.Get()
	.Load("http://example.com/images/slider.jpg")
	.Placeholder(Resource.Drawable.loading)
	.Fit()
	.CenterCrop()
	.NoFade()
	.Error(Resource.Drawable.error)
	.Into(myImageView);
```
 
## Nuget
`PM> Install-Package Rightek.Square.Picasso`

| Package Name             | NuGet                                                                       | Downloads                                                                    |
|--------------------------|-----------------------------------------------------------------------------|------------------------------------------------------------------------------|
| Rightek.Square.Picasso | [![nuget](https://img.shields.io/nuget/v/Rightek.Square.Picasso.svg?color=%23268bd2&style=flat-square)](https://www.nuget.org/packages/Rightek.Square.Picasso) | [![stats](https://img.shields.io/nuget/dt/Rightek.Square.Picasso.svg?color=%2382b414&style=flat-square)](https://www.nuget.org/stats/packages/Rightek.Square.Picasso?groupby=Version) |
| Rightek.Square.OkHttp3 | [![nuget](https://img.shields.io/nuget/v/Rightek.Square.OkHttp3.svg?color=%23268bd2&style=flat-square)](https://www.nuget.org/packages/Rightek.Square.OkHttp3) | [![stats](https://img.shields.io/nuget/dt/Rightek.Square.OkHttp3.svg?color=%2382b414&style=flat-square)](https://www.nuget.org/stats/packages/Rightek.Square.OkHttp3?groupby=Version) |
| Rightek.Square.Okio | [![nuget](https://img.shields.io/nuget/v/Rightek.Square.Okio.svg?color=%23268bd2&style=flat-square)](https://www.nuget.org/packages/Rightek.Square.Okio) | [![stats](https://img.shields.io/nuget/dt/Rightek.Square.Okio.svg?color=%2382b414&style=flat-square)](https://www.nuget.org/stats/packages/Rightek.Square.Okio?groupby=Version) |

## Dependencies
- [Xamarin binding for Okio](https://github.com/rightek/square.okio)
- [Xamarin binding for OkHttp](https://github.com/rightek/square.okhttp)

## License
MIT

---
Made with ♥ by people @ [Rightek](http://rightek.ir)
