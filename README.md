# api documentation for  [pdfjs-dist (v1.8.172)](http://mozilla.github.io/pdf.js/)  [![npm package](https://img.shields.io/npm/v/npmdoc-pdfjs-dist.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-pdfjs-dist) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-pdfjs-dist.svg)](https://travis-ci.org/npmdoc/node-npmdoc-pdfjs-dist)
#### Generic build of Mozilla's PDF.js library.

[![NPM](https://nodei.co/npm/pdfjs-dist.png?downloads=true)](https://www.npmjs.com/package/pdfjs-dist)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pdfjs-dist/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-pdfjs-dist_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pdfjs-dist/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-pdfjs-dist/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-pdfjs-dist/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "browser": {
        "node-ensure": false
    },
    "bugs": {
        "url": "https://github.com/mozilla/pdf.js/issues"
    },
    "dependencies": {
        "node-ensure": "^0.0.0",
        "worker-loader": "^0.8.0"
    },
    "description": "Generic build of Mozilla's PDF.js library.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "613da9c7ea9d8f4367f8c229a3839e290dc151c3",
        "tarball": "https://registry.npmjs.org/pdfjs-dist/-/pdfjs-dist-1.8.172.tgz"
    },
    "format": "amd",
    "gitHead": "ab1ca56288ff61e19f9028fda7cb84473fe58ce6",
    "homepage": "http://mozilla.github.io/pdf.js/",
    "keywords": [
        "Mozilla",
        "pdf",
        "pdf.js"
    ],
    "license": "Apache-2.0",
    "main": "build/pdf.js",
    "maintainers": [
        {
            "name": "brendandahl",
            "email": "brendan.dahl@gmail.com"
        },
        {
            "name": "pdfjsbot",
            "email": "dev-pdf-js@lists.mozilla.org"
        },
        {
            "name": "yurydelendik",
            "email": "ydelendik@mozilla.com"
        }
    ],
    "name": "pdfjs-dist",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mozilla/pdfjs-dist.git"
    },
    "scripts": {},
    "version": "1.8.172"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module pdfjs-dist](#apidoc.module.pdfjs-dist)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>CustomStyle ()](#apidoc.element.pdfjs-dist.CustomStyle)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>InvalidPDFException (msg)](#apidoc.element.pdfjs-dist.InvalidPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>MissingPDFException (msg)](#apidoc.element.pdfjs-dist.MissingPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFDataRangeTransport (length, initialData)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.CustomStyle ()](#apidoc.element.pdfjs-dist.PDFJS.CustomStyle)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.InvalidPDFException (msg)](#apidoc.element.pdfjs-dist.PDFJS.InvalidPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.Metadata (meta)](#apidoc.element.pdfjs-dist.PDFJS.Metadata)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.MissingPDFException (msg)](#apidoc.element.pdfjs-dist.PDFJS.MissingPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.PDFDataRangeTransport (length, initialData)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.PDFWorker (name, port)](#apidoc.element.pdfjs-dist.PDFJS.PDFWorker)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.PageViewport (viewBox, scale, rotation, offsetX, offsetY, dontFlip)](#apidoc.element.pdfjs-dist.PDFJS.PageViewport)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.PasswordException (msg, code)](#apidoc.element.pdfjs-dist.PDFJS.PasswordException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.SVGGraphics (commonObjs, objs, forceDataSchema)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.UnexpectedResponseException (msg, status)](#apidoc.element.pdfjs-dist.PDFJS.UnexpectedResponseException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.UnknownErrorException (msg, details)](#apidoc.element.pdfjs-dist.PDFJS.UnknownErrorException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.Util ()](#apidoc.element.pdfjs-dist.PDFJS.Util)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFWorker (name, port)](#apidoc.element.pdfjs-dist.PDFWorker)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>RenderingCancelledException (msg, type)](#apidoc.element.pdfjs-dist.RenderingCancelledException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>SVGGraphics (commonObjs, objs, forceDataSchema)](#apidoc.element.pdfjs-dist.SVGGraphics)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>UnexpectedResponseException (msg, status)](#apidoc.element.pdfjs-dist.UnexpectedResponseException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>addLinkAttributes (link, params)](#apidoc.element.pdfjs-dist.addLinkAttributes)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>createBlob (data, contentType)](#apidoc.element.pdfjs-dist.createBlob)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>createObjectURL (data, contentType, forceDataSchema)](#apidoc.element.pdfjs-dist.createObjectURL)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>createPromiseCapability ()](#apidoc.element.pdfjs-dist.createPromiseCapability)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>createValidAbsoluteUrl (url, baseUrl)](#apidoc.element.pdfjs-dist.createValidAbsoluteUrl)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>getDocument (src, pdfDataRangeTransport, passwordCallback, progressCallback)](#apidoc.element.pdfjs-dist.getDocument)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>getFilenameFromUrl (url)](#apidoc.element.pdfjs-dist.getFilenameFromUrl)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>isValidUrl (url, allowRelative)](#apidoc.element.pdfjs-dist.isValidUrl)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>removeNullCharacters (str)](#apidoc.element.pdfjs-dist.removeNullCharacters)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>renderTextLayer (renderParameters)](#apidoc.element.pdfjs-dist.renderTextLayer)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>shadow (obj, prop, value)](#apidoc.element.pdfjs-dist.shadow)
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>AnnotationLayer
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>OPS
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFDataRangeTransport.prototype
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.AnnotationLayer
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.Metadata.prototype
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.PDFDataRangeTransport.prototype
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.PDFWorker.prototype
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.PageViewport.prototype
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.SVGGraphics.prototype
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.UnsupportedManager
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFWorker.prototype
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>PasswordResponses
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>SVGGraphics.prototype
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>UNSUPPORTED_FEATURES
1.  object <span class="apidocSignatureSpan">pdfjs-dist.</span>pdf
1.  string <span class="apidocSignatureSpan">pdfjs-dist.</span>build
1.  string <span class="apidocSignatureSpan">pdfjs-dist.</span>version

#### [module pdfjs-dist.AnnotationLayer](#apidoc.module.pdfjs-dist.AnnotationLayer)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.AnnotationLayer.</span>render (parameters)](#apidoc.element.pdfjs-dist.AnnotationLayer.render)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.AnnotationLayer.</span>update (parameters)](#apidoc.element.pdfjs-dist.AnnotationLayer.update)

#### [module pdfjs-dist.CustomStyle](#apidoc.module.pdfjs-dist.CustomStyle)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>CustomStyle ()](#apidoc.element.pdfjs-dist.CustomStyle.CustomStyle)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.CustomStyle.</span>getProp (propName, element)](#apidoc.element.pdfjs-dist.CustomStyle.getProp)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.CustomStyle.</span>setProp (propName, element, str)](#apidoc.element.pdfjs-dist.CustomStyle.setProp)

#### [module pdfjs-dist.InvalidPDFException](#apidoc.module.pdfjs-dist.InvalidPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>InvalidPDFException (msg)](#apidoc.element.pdfjs-dist.InvalidPDFException.InvalidPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.InvalidPDFException.</span>constructor (msg)](#apidoc.element.pdfjs-dist.InvalidPDFException.constructor)

#### [module pdfjs-dist.MissingPDFException](#apidoc.module.pdfjs-dist.MissingPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>MissingPDFException (msg)](#apidoc.element.pdfjs-dist.MissingPDFException.MissingPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.MissingPDFException.</span>constructor (msg)](#apidoc.element.pdfjs-dist.MissingPDFException.constructor)

#### [module pdfjs-dist.PDFDataRangeTransport](#apidoc.module.pdfjs-dist.PDFDataRangeTransport)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFDataRangeTransport (length, initialData)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.PDFDataRangeTransport)

#### [module pdfjs-dist.PDFDataRangeTransport.prototype](#apidoc.module.pdfjs-dist.PDFDataRangeTransport.prototype)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>abort ()](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.abort)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>addProgressListener (listener)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.addProgressListener)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>addProgressiveReadListener (listener)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.addProgressiveReadListener)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>addRangeListener (listener)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.addRangeListener)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>onDataProgress (loaded)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.onDataProgress)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>onDataProgressiveRead (chunk)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.onDataProgressiveRead)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>onDataRange (begin, chunk)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.onDataRange)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>requestDataRange (begin, end)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.requestDataRange)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>transportReady ()](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.transportReady)

#### [module pdfjs-dist.PDFJS](#apidoc.module.pdfjs-dist.PDFJS)
1.  boolean <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>cMapPacked
1.  boolean <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>compatibilityChecked
1.  boolean <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>disableAutoFetch
1.  boolean <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>disableCreateObjectURL
1.  boolean <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>disableFontFace
1.  boolean <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>disableRange
1.  boolean <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>disableStream
1.  boolean <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>disableWebGL
1.  boolean <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>disableWorker
1.  boolean <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>isEvalSupported
1.  boolean <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>openExternalLinksInNewWindow
1.  boolean <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>pdfBug
1.  boolean <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>pdfjsNext
1.  boolean <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>postMessageTransfers
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>CustomStyle ()](#apidoc.element.pdfjs-dist.PDFJS.CustomStyle)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>InvalidPDFException (msg)](#apidoc.element.pdfjs-dist.PDFJS.InvalidPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>Metadata (meta)](#apidoc.element.pdfjs-dist.PDFJS.Metadata)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>MissingPDFException (msg)](#apidoc.element.pdfjs-dist.PDFJS.MissingPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PDFDataRangeTransport (length, initialData)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PDFWorker (name, port)](#apidoc.element.pdfjs-dist.PDFJS.PDFWorker)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PageViewport (viewBox, scale, rotation, offsetX, offsetY, dontFlip)](#apidoc.element.pdfjs-dist.PDFJS.PageViewport)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PasswordException (msg, code)](#apidoc.element.pdfjs-dist.PDFJS.PasswordException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>SVGGraphics (commonObjs, objs, forceDataSchema)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>UnexpectedResponseException (msg, status)](#apidoc.element.pdfjs-dist.PDFJS.UnexpectedResponseException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>UnknownErrorException (msg, details)](#apidoc.element.pdfjs-dist.PDFJS.UnknownErrorException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>Util ()](#apidoc.element.pdfjs-dist.PDFJS.Util)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>addLinkAttributes (link, params)](#apidoc.element.pdfjs-dist.PDFJS.addLinkAttributes)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>createBlob (data, contentType)](#apidoc.element.pdfjs-dist.PDFJS.createBlob)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>createObjectURL (data, contentType)](#apidoc.element.pdfjs-dist.PDFJS.createObjectURL)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>createPromiseCapability ()](#apidoc.element.pdfjs-dist.PDFJS.createPromiseCapability)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>getDocument (src, pdfDataRangeTransport, passwordCallback, progressCallback)](#apidoc.element.pdfjs-dist.PDFJS.getDocument)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>getFilenameFromUrl (url)](#apidoc.element.pdfjs-dist.PDFJS.getFilenameFromUrl)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>isExternalLinkTargetSet ()](#apidoc.element.pdfjs-dist.PDFJS.isExternalLinkTargetSet)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>isValidUrl (url, allowRelative)](#apidoc.element.pdfjs-dist.PDFJS.isValidUrl)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>removeNullCharacters (str)](#apidoc.element.pdfjs-dist.PDFJS.removeNullCharacters)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>renderTextLayer (renderParameters)](#apidoc.element.pdfjs-dist.PDFJS.renderTextLayer)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>shadow (obj, prop, value)](#apidoc.element.pdfjs-dist.PDFJS.shadow)
1.  number <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>externalLinkTarget
1.  number <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>maxImageSize
1.  number <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>verbosity
1.  object <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>AnnotationLayer
1.  object <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>LinkTarget
1.  object <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>OPS
1.  object <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PasswordResponses
1.  object <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>UNSUPPORTED_FEATURES
1.  object <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>UnsupportedManager
1.  object <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>VERBOSITY_LEVELS
1.  object <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>cMapUrl
1.  object <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>workerPort
1.  object <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>workerSrc
1.  string <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>build
1.  string <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>externalLinkRel
1.  string <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>imageResourcesPath
1.  string <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>version

#### [module pdfjs-dist.PDFJS.AnnotationLayer](#apidoc.module.pdfjs-dist.PDFJS.AnnotationLayer)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.AnnotationLayer.</span>render (parameters)](#apidoc.element.pdfjs-dist.PDFJS.AnnotationLayer.render)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.AnnotationLayer.</span>update (parameters)](#apidoc.element.pdfjs-dist.PDFJS.AnnotationLayer.update)

#### [module pdfjs-dist.PDFJS.CustomStyle](#apidoc.module.pdfjs-dist.PDFJS.CustomStyle)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>CustomStyle ()](#apidoc.element.pdfjs-dist.PDFJS.CustomStyle.CustomStyle)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.CustomStyle.</span>getProp (propName, element)](#apidoc.element.pdfjs-dist.PDFJS.CustomStyle.getProp)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.CustomStyle.</span>setProp (propName, element, str)](#apidoc.element.pdfjs-dist.PDFJS.CustomStyle.setProp)

#### [module pdfjs-dist.PDFJS.InvalidPDFException](#apidoc.module.pdfjs-dist.PDFJS.InvalidPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>InvalidPDFException (msg)](#apidoc.element.pdfjs-dist.PDFJS.InvalidPDFException.InvalidPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.InvalidPDFException.</span>constructor (msg)](#apidoc.element.pdfjs-dist.PDFJS.InvalidPDFException.constructor)

#### [module pdfjs-dist.PDFJS.Metadata](#apidoc.module.pdfjs-dist.PDFJS.Metadata)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>Metadata (meta)](#apidoc.element.pdfjs-dist.PDFJS.Metadata.Metadata)

#### [module pdfjs-dist.PDFJS.Metadata.prototype](#apidoc.module.pdfjs-dist.PDFJS.Metadata.prototype)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Metadata.prototype.</span>get (name)](#apidoc.element.pdfjs-dist.PDFJS.Metadata.prototype.get)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Metadata.prototype.</span>has (name)](#apidoc.element.pdfjs-dist.PDFJS.Metadata.prototype.has)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Metadata.prototype.</span>parse ()](#apidoc.element.pdfjs-dist.PDFJS.Metadata.prototype.parse)

#### [module pdfjs-dist.PDFJS.MissingPDFException](#apidoc.module.pdfjs-dist.PDFJS.MissingPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>MissingPDFException (msg)](#apidoc.element.pdfjs-dist.PDFJS.MissingPDFException.MissingPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.MissingPDFException.</span>constructor (msg)](#apidoc.element.pdfjs-dist.PDFJS.MissingPDFException.constructor)

#### [module pdfjs-dist.PDFJS.PDFDataRangeTransport](#apidoc.module.pdfjs-dist.PDFJS.PDFDataRangeTransport)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PDFDataRangeTransport (length, initialData)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.PDFDataRangeTransport)

#### [module pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype](#apidoc.module.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>abort ()](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.abort)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>addProgressListener (listener)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.addProgressListener)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>addProgressiveReadListener (listener)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.addProgressiveReadListener)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>addRangeListener (listener)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.addRangeListener)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>onDataProgress (loaded)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.onDataProgress)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>onDataProgressiveRead (chunk)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.onDataProgressiveRead)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>onDataRange (begin, chunk)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.onDataRange)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>requestDataRange (begin, end)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.requestDataRange)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>transportReady ()](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.transportReady)

#### [module pdfjs-dist.PDFJS.PDFWorker](#apidoc.module.pdfjs-dist.PDFJS.PDFWorker)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PDFWorker (name, port)](#apidoc.element.pdfjs-dist.PDFJS.PDFWorker.PDFWorker)

#### [module pdfjs-dist.PDFJS.PDFWorker.prototype](#apidoc.module.pdfjs-dist.PDFJS.PDFWorker.prototype)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFWorker.prototype.</span>_initialize ()](#apidoc.element.pdfjs-dist.PDFJS.PDFWorker.prototype._initialize)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFWorker.prototype.</span>_initializeFromPort (port)](#apidoc.element.pdfjs-dist.PDFJS.PDFWorker.prototype._initializeFromPort)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFWorker.prototype.</span>_setupFakeWorker ()](#apidoc.element.pdfjs-dist.PDFJS.PDFWorker.prototype._setupFakeWorker)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFWorker.prototype.</span>destroy ()](#apidoc.element.pdfjs-dist.PDFJS.PDFWorker.prototype.destroy)

#### [module pdfjs-dist.PDFJS.PageViewport](#apidoc.module.pdfjs-dist.PDFJS.PageViewport)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PageViewport (viewBox, scale, rotation, offsetX, offsetY, dontFlip)](#apidoc.element.pdfjs-dist.PDFJS.PageViewport.PageViewport)

#### [module pdfjs-dist.PDFJS.PageViewport.prototype](#apidoc.module.pdfjs-dist.PDFJS.PageViewport.prototype)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PageViewport.prototype.</span>clone (args)](#apidoc.element.pdfjs-dist.PDFJS.PageViewport.prototype.clone)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PageViewport.prototype.</span>convertToPdfPoint (x, y)](#apidoc.element.pdfjs-dist.PDFJS.PageViewport.prototype.convertToPdfPoint)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PageViewport.prototype.</span>convertToViewportPoint (x, y)](#apidoc.element.pdfjs-dist.PDFJS.PageViewport.prototype.convertToViewportPoint)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PageViewport.prototype.</span>convertToViewportRectangle (rect)](#apidoc.element.pdfjs-dist.PDFJS.PageViewport.prototype.convertToViewportRectangle)

#### [module pdfjs-dist.PDFJS.PasswordException](#apidoc.module.pdfjs-dist.PDFJS.PasswordException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PasswordException (msg, code)](#apidoc.element.pdfjs-dist.PDFJS.PasswordException.PasswordException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PasswordException.</span>constructor (msg, code)](#apidoc.element.pdfjs-dist.PDFJS.PasswordException.constructor)

#### [module pdfjs-dist.PDFJS.SVGGraphics](#apidoc.module.pdfjs-dist.PDFJS.SVGGraphics)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>SVGGraphics (commonObjs, objs, forceDataSchema)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.SVGGraphics)

#### [module pdfjs-dist.PDFJS.SVGGraphics.prototype](#apidoc.module.pdfjs-dist.PDFJS.SVGGraphics.prototype)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>_ensureClipGroup ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype._ensureClipGroup)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>_ensureTransformGroup ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype._ensureTransformGroup)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>_initialize (viewport)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype._initialize)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>addFontStyle (fontObj)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.addFontStyle)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>beginText ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.beginText)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>clip (type)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.clip)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>closeFillStroke ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.closeFillStroke)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>closePath ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.closePath)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>closeStroke ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.closeStroke)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>constructPath (ops, args)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.constructPath)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>convertOpList (operatorList)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.convertOpList)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>endPath ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.endPath)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>endText ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.endText)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>eoFill ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.eoFill)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>eoFillStroke ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.eoFillStroke)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>executeOpTree (opTree)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.executeOpTree)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>fill ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.fill)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>fillStroke ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.fillStroke)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>getSVG (operatorList, viewport)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.getSVG)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>group (items)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.group)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>loadDependencies (operatorList)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.loadDependencies)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>moveText (x, y)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.moveText)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>nextLine ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.nextLine)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>paintFormXObjectBegin (matrix, bbox)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintFormXObjectBegin)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>paintFormXObjectEnd ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintFormXObjectEnd)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>paintImageMaskXObject (imgData)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintImageMaskXObject)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>paintImageXObject (objId)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintImageXObject)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>paintInlineImageXObject (imgData, mask)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintInlineImageXObject)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>paintJpegXObject (objId, w, h)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintJpegXObject)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>paintSolidColorImageMask ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintSolidColorImageMask)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>restore ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.restore)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>save ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.save)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setCharSpacing (charSpacing)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setCharSpacing)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setDash (dashArray, dashPhase)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setDash)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setFillRGBColor (r, g, b)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setFillRGBColor)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setFont (details)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setFont)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setGState (states)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setGState)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setHScale (scale)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setHScale)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setLeading (leading)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setLeading)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setLeadingMoveText (x, y)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setLeadingMoveText)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setLineCap (style)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setLineCap)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setLineJoin (style)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setLineJoin)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setLineWidth (width)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setLineWidth)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setMiterLimit (limit)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setMiterLimit)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setStrokeRGBColor (r, g, b)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setStrokeRGBColor)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setTextMatrix (a, b, c, d, e, f)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setTextMatrix)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setTextRise (textRise)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setTextRise)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setWordSpacing (wordSpacing)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setWordSpacing)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>showText (glyphs)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.showText)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>stroke ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.stroke)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>transform (a, b, c, d, e, f)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.transform)

#### [module pdfjs-dist.PDFJS.UnexpectedResponseException](#apidoc.module.pdfjs-dist.PDFJS.UnexpectedResponseException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>UnexpectedResponseException (msg, status)](#apidoc.element.pdfjs-dist.PDFJS.UnexpectedResponseException.UnexpectedResponseException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.UnexpectedResponseException.</span>constructor (msg, status)](#apidoc.element.pdfjs-dist.PDFJS.UnexpectedResponseException.constructor)

#### [module pdfjs-dist.PDFJS.UnknownErrorException](#apidoc.module.pdfjs-dist.PDFJS.UnknownErrorException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>UnknownErrorException (msg, details)](#apidoc.element.pdfjs-dist.PDFJS.UnknownErrorException.UnknownErrorException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.UnknownErrorException.</span>constructor (msg, details)](#apidoc.element.pdfjs-dist.PDFJS.UnknownErrorException.constructor)

#### [module pdfjs-dist.PDFJS.UnsupportedManager](#apidoc.module.pdfjs-dist.PDFJS.UnsupportedManager)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.UnsupportedManager.</span>listen (cb)](#apidoc.element.pdfjs-dist.PDFJS.UnsupportedManager.listen)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.UnsupportedManager.</span>notify (featureId)](#apidoc.element.pdfjs-dist.PDFJS.UnsupportedManager.notify)

#### [module pdfjs-dist.PDFJS.Util](#apidoc.module.pdfjs-dist.PDFJS.Util)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>Util ()](#apidoc.element.pdfjs-dist.PDFJS.Util.Util)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>appendToArray (arr1, arr2)](#apidoc.element.pdfjs-dist.PDFJS.Util.appendToArray)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>apply3dTransform (m, v)](#apidoc.element.pdfjs-dist.PDFJS.Util.apply3dTransform)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>applyInverseTransform (p, m)](#apidoc.element.pdfjs-dist.PDFJS.Util.applyInverseTransform)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>applyTransform (p, m)](#apidoc.element.pdfjs-dist.PDFJS.Util.applyTransform)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>extendObj (obj1, obj2)](#apidoc.element.pdfjs-dist.PDFJS.Util.extendObj)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>getAxialAlignedBoundingBox (r, m)](#apidoc.element.pdfjs-dist.PDFJS.Util.getAxialAlignedBoundingBox)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>getInheritableProperty (dict, name, getArray)](#apidoc.element.pdfjs-dist.PDFJS.Util.getInheritableProperty)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>inherit (sub, base, prototype)](#apidoc.element.pdfjs-dist.PDFJS.Util.inherit)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>intersect (rect1, rect2)](#apidoc.element.pdfjs-dist.PDFJS.Util.intersect)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>inverseTransform (m)](#apidoc.element.pdfjs-dist.PDFJS.Util.inverseTransform)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>loadScript (src, callback)](#apidoc.element.pdfjs-dist.PDFJS.Util.loadScript)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>makeCssRgb (r, g, b)](#apidoc.element.pdfjs-dist.PDFJS.Util.makeCssRgb)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>normalizeRect (rect)](#apidoc.element.pdfjs-dist.PDFJS.Util.normalizeRect)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>prependToArray (arr1, arr2)](#apidoc.element.pdfjs-dist.PDFJS.Util.prependToArray)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>sign (num)](#apidoc.element.pdfjs-dist.PDFJS.Util.sign)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>singularValueDecompose2dScale (m)](#apidoc.element.pdfjs-dist.PDFJS.Util.singularValueDecompose2dScale)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>toRoman (number, lowerCase)](#apidoc.element.pdfjs-dist.PDFJS.Util.toRoman)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>transform (m1, m2)](#apidoc.element.pdfjs-dist.PDFJS.Util.transform)

#### [module pdfjs-dist.PDFWorker](#apidoc.module.pdfjs-dist.PDFWorker)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFWorker (name, port)](#apidoc.element.pdfjs-dist.PDFWorker.PDFWorker)

#### [module pdfjs-dist.PDFWorker.prototype](#apidoc.module.pdfjs-dist.PDFWorker.prototype)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFWorker.prototype.</span>_initialize ()](#apidoc.element.pdfjs-dist.PDFWorker.prototype._initialize)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFWorker.prototype.</span>_initializeFromPort (port)](#apidoc.element.pdfjs-dist.PDFWorker.prototype._initializeFromPort)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFWorker.prototype.</span>_setupFakeWorker ()](#apidoc.element.pdfjs-dist.PDFWorker.prototype._setupFakeWorker)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.PDFWorker.prototype.</span>destroy ()](#apidoc.element.pdfjs-dist.PDFWorker.prototype.destroy)

#### [module pdfjs-dist.RenderingCancelledException](#apidoc.module.pdfjs-dist.RenderingCancelledException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>RenderingCancelledException (msg, type)](#apidoc.element.pdfjs-dist.RenderingCancelledException.RenderingCancelledException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.RenderingCancelledException.</span>constructor (msg, type)](#apidoc.element.pdfjs-dist.RenderingCancelledException.constructor)

#### [module pdfjs-dist.SVGGraphics](#apidoc.module.pdfjs-dist.SVGGraphics)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>SVGGraphics (commonObjs, objs, forceDataSchema)](#apidoc.element.pdfjs-dist.SVGGraphics.SVGGraphics)

#### [module pdfjs-dist.SVGGraphics.prototype](#apidoc.module.pdfjs-dist.SVGGraphics.prototype)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>_ensureClipGroup ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype._ensureClipGroup)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>_ensureTransformGroup ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype._ensureTransformGroup)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>_initialize (viewport)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype._initialize)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>addFontStyle (fontObj)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.addFontStyle)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>beginText ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.beginText)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>clip (type)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.clip)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>closeFillStroke ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.closeFillStroke)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>closePath ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.closePath)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>closeStroke ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.closeStroke)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>constructPath (ops, args)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.constructPath)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>convertOpList (operatorList)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.convertOpList)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>endPath ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.endPath)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>endText ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.endText)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>eoFill ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.eoFill)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>eoFillStroke ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.eoFillStroke)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>executeOpTree (opTree)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.executeOpTree)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>fill ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.fill)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>fillStroke ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.fillStroke)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>getSVG (operatorList, viewport)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.getSVG)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>group (items)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.group)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>loadDependencies (operatorList)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.loadDependencies)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>moveText (x, y)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.moveText)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>nextLine ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.nextLine)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>paintFormXObjectBegin (matrix, bbox)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintFormXObjectBegin)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>paintFormXObjectEnd ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintFormXObjectEnd)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>paintImageMaskXObject (imgData)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintImageMaskXObject)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>paintImageXObject (objId)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintImageXObject)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>paintInlineImageXObject (imgData, mask)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintInlineImageXObject)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>paintJpegXObject (objId, w, h)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintJpegXObject)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>paintSolidColorImageMask ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintSolidColorImageMask)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>restore ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.restore)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>save ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.save)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setCharSpacing (charSpacing)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setCharSpacing)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setDash (dashArray, dashPhase)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setDash)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setFillRGBColor (r, g, b)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setFillRGBColor)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setFont (details)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setFont)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setGState (states)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setGState)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setHScale (scale)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setHScale)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setLeading (leading)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setLeading)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setLeadingMoveText (x, y)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setLeadingMoveText)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setLineCap (style)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setLineCap)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setLineJoin (style)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setLineJoin)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setLineWidth (width)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setLineWidth)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setMiterLimit (limit)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setMiterLimit)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setStrokeRGBColor (r, g, b)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setStrokeRGBColor)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setTextMatrix (a, b, c, d, e, f)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setTextMatrix)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setTextRise (textRise)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setTextRise)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setWordSpacing (wordSpacing)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setWordSpacing)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>showText (glyphs)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.showText)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>stroke ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.stroke)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>transform (a, b, c, d, e, f)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.transform)

#### [module pdfjs-dist.UnexpectedResponseException](#apidoc.module.pdfjs-dist.UnexpectedResponseException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.</span>UnexpectedResponseException (msg, status)](#apidoc.element.pdfjs-dist.UnexpectedResponseException.UnexpectedResponseException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.UnexpectedResponseException.</span>constructor (msg, status)](#apidoc.element.pdfjs-dist.UnexpectedResponseException.constructor)

#### [module pdfjs-dist.pdf](#apidoc.module.pdfjs-dist.pdf)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>CustomStyle ()](#apidoc.element.pdfjs-dist.pdf.CustomStyle)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>InvalidPDFException (msg)](#apidoc.element.pdfjs-dist.pdf.InvalidPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>MissingPDFException (msg)](#apidoc.element.pdfjs-dist.pdf.MissingPDFException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>PDFDataRangeTransport (length, initialData)](#apidoc.element.pdfjs-dist.pdf.PDFDataRangeTransport)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>PDFWorker (name, port)](#apidoc.element.pdfjs-dist.pdf.PDFWorker)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>RenderingCancelledException (msg, type)](#apidoc.element.pdfjs-dist.pdf.RenderingCancelledException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>SVGGraphics (commonObjs, objs, forceDataSchema)](#apidoc.element.pdfjs-dist.pdf.SVGGraphics)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>UnexpectedResponseException (msg, status)](#apidoc.element.pdfjs-dist.pdf.UnexpectedResponseException)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>addLinkAttributes (link, params)](#apidoc.element.pdfjs-dist.pdf.addLinkAttributes)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>createBlob (data, contentType)](#apidoc.element.pdfjs-dist.pdf.createBlob)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>createObjectURL (data, contentType, forceDataSchema)](#apidoc.element.pdfjs-dist.pdf.createObjectURL)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>createPromiseCapability ()](#apidoc.element.pdfjs-dist.pdf.createPromiseCapability)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>createValidAbsoluteUrl (url, baseUrl)](#apidoc.element.pdfjs-dist.pdf.createValidAbsoluteUrl)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>getDocument (src, pdfDataRangeTransport, passwordCallback, progressCallback)](#apidoc.element.pdfjs-dist.pdf.getDocument)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>getFilenameFromUrl (url)](#apidoc.element.pdfjs-dist.pdf.getFilenameFromUrl)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>isValidUrl (url, allowRelative)](#apidoc.element.pdfjs-dist.pdf.isValidUrl)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>removeNullCharacters (str)](#apidoc.element.pdfjs-dist.pdf.removeNullCharacters)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>renderTextLayer (renderParameters)](#apidoc.element.pdfjs-dist.pdf.renderTextLayer)
1.  [function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>shadow (obj, prop, value)](#apidoc.element.pdfjs-dist.pdf.shadow)
1.  object <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>AnnotationLayer
1.  object <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>OPS
1.  object <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>PDFJS
1.  object <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>PasswordResponses
1.  object <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>UNSUPPORTED_FEATURES
1.  string <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>build
1.  string <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>version



# <a name="apidoc.module.pdfjs-dist"></a>[module pdfjs-dist](#apidoc.module.pdfjs-dist)

#### <a name="apidoc.element.pdfjs-dist.CustomStyle"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>CustomStyle ()](#apidoc.element.pdfjs-dist.CustomStyle)
- description and source-code
```javascript
function CustomStyle() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.InvalidPDFException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>InvalidPDFException (msg)](#apidoc.element.pdfjs-dist.InvalidPDFException)
- description and source-code
```javascript
function InvalidPDFException(msg) {
  this.name = 'InvalidPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.MissingPDFException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>MissingPDFException (msg)](#apidoc.element.pdfjs-dist.MissingPDFException)
- description and source-code
```javascript
function MissingPDFException(msg) {
  this.name = 'MissingPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFDataRangeTransport"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFDataRangeTransport (length, initialData)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport)
- description and source-code
```javascript
function PDFDataRangeTransport(length, initialData) {
  this.length = length;
  this.initialData = initialData;
  this._rangeListeners = [];
  this._progressListeners = [];
  this._progressiveReadListeners = [];
  this._readyCapability = createPromiseCapability();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.CustomStyle"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.CustomStyle ()](#apidoc.element.pdfjs-dist.PDFJS.CustomStyle)
- description and source-code
```javascript
function CustomStyle() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.InvalidPDFException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.InvalidPDFException (msg)](#apidoc.element.pdfjs-dist.PDFJS.InvalidPDFException)
- description and source-code
```javascript
function InvalidPDFException(msg) {
  this.name = 'InvalidPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Metadata"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.Metadata (meta)](#apidoc.element.pdfjs-dist.PDFJS.Metadata)
- description and source-code
```javascript
function Metadata(meta) {
  if (typeof meta === 'string') {
    meta = fixMetadata(meta);
    var parser = new DOMParser();
    meta = parser.parseFromString(meta, 'application/xml');
  } else if (!(meta instanceof Document)) {
    error('Metadata: Invalid metadata object');
  }
  this.metaDocument = meta;
  this.metadata = Object.create(null);
  this.parse();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.MissingPDFException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.MissingPDFException (msg)](#apidoc.element.pdfjs-dist.PDFJS.MissingPDFException)
- description and source-code
```javascript
function MissingPDFException(msg) {
  this.name = 'MissingPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.PDFDataRangeTransport (length, initialData)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport)
- description and source-code
```javascript
function PDFDataRangeTransport(length, initialData) {
  this.length = length;
  this.initialData = initialData;
  this._rangeListeners = [];
  this._progressListeners = [];
  this._progressiveReadListeners = [];
  this._readyCapability = createPromiseCapability();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFWorker"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.PDFWorker (name, port)](#apidoc.element.pdfjs-dist.PDFJS.PDFWorker)
- description and source-code
```javascript
function PDFWorker(name, port) {
  this.name = name;
  this.destroyed = false;
  this._readyCapability = createPromiseCapability();
  this._port = null;
  this._webWorker = null;
  this._messageHandler = null;
  if (port) {
    this._initializeFromPort(port);
    return;
  }
  this._initialize();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PageViewport"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.PageViewport (viewBox, scale, rotation, offsetX, offsetY, dontFlip)](#apidoc.element.pdfjs-dist.PDFJS.PageViewport)
- description and source-code
```javascript
function PageViewport(viewBox, scale, rotation, offsetX, offsetY, dontFlip) {
  this.viewBox = viewBox;
  this.scale = scale;
  this.rotation = rotation;
  this.offsetX = offsetX;
  this.offsetY = offsetY;
  var centerX = (viewBox[2] + viewBox[0]) / 2;
  var centerY = (viewBox[3] + viewBox[1]) / 2;
  var rotateA, rotateB, rotateC, rotateD;
  rotation = rotation % 360;
  rotation = rotation < 0 ? rotation + 360 : rotation;
  switch (rotation) {
    case 180:
      rotateA = -1;
      rotateB = 0;
      rotateC = 0;
      rotateD = 1;
      break;
    case 90:
      rotateA = 0;
      rotateB = 1;
      rotateC = 1;
      rotateD = 0;
      break;
    case 270:
      rotateA = 0;
      rotateB = -1;
      rotateC = -1;
      rotateD = 0;
      break;
    default:
      rotateA = 1;
      rotateB = 0;
      rotateC = 0;
      rotateD = -1;
      break;
  }
  if (dontFlip) {
    rotateC = -rotateC;
    rotateD = -rotateD;
  }
  var offsetCanvasX, offsetCanvasY;
  var width, height;
  if (rotateA === 0) {
    offsetCanvasX = Math.abs(centerY - viewBox[1]) * scale + offsetX;
    offsetCanvasY = Math.abs(centerX - viewBox[0]) * scale + offsetY;
    width = Math.abs(viewBox[3] - viewBox[1]) * scale;
    height = Math.abs(viewBox[2] - viewBox[0]) * scale;
  } else {
    offsetCanvasX = Math.abs(centerX - viewBox[0]) * scale + offsetX;
    offsetCanvasY = Math.abs(centerY - viewBox[1]) * scale + offsetY;
    width = Math.abs(viewBox[2] - viewBox[0]) * scale;
    height = Math.abs(viewBox[3] - viewBox[1]) * scale;
  }
  this.transform = [rotateA * scale, rotateB * scale, rotateC * scale, rotateD * scale, offsetCanvasX - rotateA * scale * centerX
 - rotateC * scale * centerY, offsetCanvasY - rotateB * scale * centerX - rotateD * scale * centerY];
  this.width = width;
  this.height = height;
  this.fontScale = scale;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PasswordException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.PasswordException (msg, code)](#apidoc.element.pdfjs-dist.PDFJS.PasswordException)
- description and source-code
```javascript
function PasswordException(msg, code) {
  this.name = 'PasswordException';
  this.message = msg;
  this.code = code;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.SVGGraphics (commonObjs, objs, forceDataSchema)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics)
- description and source-code
```javascript
function SVGGraphics(commonObjs, objs, forceDataSchema) {
  this.current = new SVGExtraState();
  this.transformMatrix = IDENTITY_MATRIX;
  this.transformStack = [];
  this.extraStack = [];
  this.commonObjs = commonObjs;
  this.objs = objs;
  this.pendingEOFill = false;
  this.embedFonts = false;
  this.embeddedFonts = Object.create(null);
  this.cssStyle = null;
  this.forceDataSchema = !!forceDataSchema;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.UnexpectedResponseException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.UnexpectedResponseException (msg, status)](#apidoc.element.pdfjs-dist.PDFJS.UnexpectedResponseException)
- description and source-code
```javascript
function UnexpectedResponseException(msg, status) {
  this.name = 'UnexpectedResponseException';
  this.message = msg;
  this.status = status;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.UnknownErrorException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.UnknownErrorException (msg, details)](#apidoc.element.pdfjs-dist.PDFJS.UnknownErrorException)
- description and source-code
```javascript
function UnknownErrorException(msg, details) {
  this.name = 'UnknownErrorException';
  this.message = msg;
  this.details = details;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFJS.Util ()](#apidoc.element.pdfjs-dist.PDFJS.Util)
- description and source-code
```javascript
function Util() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFWorker"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFWorker (name, port)](#apidoc.element.pdfjs-dist.PDFWorker)
- description and source-code
```javascript
function PDFWorker(name, port) {
  this.name = name;
  this.destroyed = false;
  this._readyCapability = createPromiseCapability();
  this._port = null;
  this._webWorker = null;
  this._messageHandler = null;
  if (port) {
    this._initializeFromPort(port);
    return;
  }
  this._initialize();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.RenderingCancelledException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>RenderingCancelledException (msg, type)](#apidoc.element.pdfjs-dist.RenderingCancelledException)
- description and source-code
```javascript
function RenderingCancelledException(msg, type) {
  this.message = msg;
  this.type = type;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>SVGGraphics (commonObjs, objs, forceDataSchema)](#apidoc.element.pdfjs-dist.SVGGraphics)
- description and source-code
```javascript
function SVGGraphics(commonObjs, objs, forceDataSchema) {
  this.current = new SVGExtraState();
  this.transformMatrix = IDENTITY_MATRIX;
  this.transformStack = [];
  this.extraStack = [];
  this.commonObjs = commonObjs;
  this.objs = objs;
  this.pendingEOFill = false;
  this.embedFonts = false;
  this.embeddedFonts = Object.create(null);
  this.cssStyle = null;
  this.forceDataSchema = !!forceDataSchema;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.UnexpectedResponseException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>UnexpectedResponseException (msg, status)](#apidoc.element.pdfjs-dist.UnexpectedResponseException)
- description and source-code
```javascript
function UnexpectedResponseException(msg, status) {
  this.name = 'UnexpectedResponseException';
  this.message = msg;
  this.status = status;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.addLinkAttributes"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>addLinkAttributes (link, params)](#apidoc.element.pdfjs-dist.addLinkAttributes)
- description and source-code
```javascript
function addLinkAttributes(link, params) {
  var url = params && params.url;
  link.href = link.title = url ? removeNullCharacters(url) : '';
  if (url) {
    var target = params.target;
    if (typeof target === 'undefined') {
      target = getDefaultSetting('externalLinkTarget');
    }
    link.target = LinkTargetStringMap[target];
    var rel = params.rel;
    if (typeof rel === 'undefined') {
      rel = getDefaultSetting('externalLinkRel');
    }
    link.rel = rel;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.createBlob"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>createBlob (data, contentType)](#apidoc.element.pdfjs-dist.createBlob)
- description and source-code
```javascript
function createBlob(data, contentType) {
  if (typeof Blob !== 'undefined') {
    return new Blob([data], { type: contentType });
  }
  warn('The "Blob" constructor is not supported.');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.createObjectURL"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>createObjectURL (data, contentType, forceDataSchema)](#apidoc.element.pdfjs-dist.createObjectURL)
- description and source-code
```javascript
function createObjectURL(data, contentType, forceDataSchema) {
  if (!forceDataSchema && typeof URL !== 'undefined' && URL.createObjectURL) {
    var blob = createBlob(data, contentType);
    return URL.createObjectURL(blob);
  }
  var buffer = 'data:' + contentType + ';base64,';
  for (var i = 0, ii = data.length; i < ii; i += 3) {
    var b1 = data[i] & 0xFF;
    var b2 = data[i + 1] & 0xFF;
    var b3 = data[i + 2] & 0xFF;
    var d1 = b1 >> 2,
        d2 = (b1 & 3) << 4 | b2 >> 4;
    var d3 = i + 1 < ii ? (b2 & 0xF) << 2 | b3 >> 6 : 64;
    var d4 = i + 2 < ii ? b3 & 0x3F : 64;
    buffer += digits[d1] + digits[d2] + digits[d3] + digits[d4];
  }
  return buffer;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.createPromiseCapability"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>createPromiseCapability ()](#apidoc.element.pdfjs-dist.createPromiseCapability)
- description and source-code
```javascript
function createPromiseCapability() {
  var capability = {};
  capability.promise = new Promise(function (resolve, reject) {
    capability.resolve = resolve;
    capability.reject = reject;
  });
  return capability;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.createValidAbsoluteUrl"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>createValidAbsoluteUrl (url, baseUrl)](#apidoc.element.pdfjs-dist.createValidAbsoluteUrl)
- description and source-code
```javascript
function createValidAbsoluteUrl(url, baseUrl) {
  if (!url) {
    return null;
  }
  try {
    var absoluteUrl = baseUrl ? new URL(url, baseUrl) : new URL(url);
    if (isValidProtocol(absoluteUrl)) {
      return absoluteUrl;
    }
  } catch (ex) {}
  return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.getDocument"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>getDocument (src, pdfDataRangeTransport, passwordCallback, progressCallback)](#apidoc.element.pdfjs-dist.getDocument)
- description and source-code
```javascript
function getDocument(src, pdfDataRangeTransport, passwordCallback, progressCallback) {
  var task = new PDFDocumentLoadingTask();
  if (arguments.length > 1) {
    deprecated('getDocument is called with pdfDataRangeTransport, ' + 'passwordCallback or progressCallback argument');
  }
  if (pdfDataRangeTransport) {
    if (!(pdfDataRangeTransport instanceof PDFDataRangeTransport)) {
      pdfDataRangeTransport = Object.create(pdfDataRangeTransport);
      pdfDataRangeTransport.length = src.length;
      pdfDataRangeTransport.initialData = src.initialData;
      if (!pdfDataRangeTransport.abort) {
        pdfDataRangeTransport.abort = function () {};
      }
    }
    src = Object.create(src);
    src.range = pdfDataRangeTransport;
  }
  task.onPassword = passwordCallback || null;
  task.onProgress = progressCallback || null;
  var source;
  if (typeof src === 'string') {
    source = { url: src };
  } else if (isArrayBuffer(src)) {
    source = { data: src };
  } else if (src instanceof PDFDataRangeTransport) {
    source = { range: src };
  } else {
    if (typeof src !== 'object') {
      error('Invalid parameter in getDocument, need either Uint8Array, ' + 'string or a parameter object');
    }
    if (!src.url && !src.data && !src.range) {
      error('Invalid parameter object: need either .data, .range or .url');
    }
    source = src;
  }
  var params = {};
  var rangeTransport = null;
  var worker = null;
  for (var key in source) {
    if (key === 'url' && typeof window !== 'undefined') {
      params[key] = new URL(source[key], window.location).href;
      continue;
    } else if (key === 'range') {
      rangeTransport = source[key];
      continue;
    } else if (key === 'worker') {
      worker = source[key];
      continue;
    } else if (key === 'data' && !(source[key] instanceof Uint8Array)) {
      var pdfBytes = source[key];
      if (typeof pdfBytes === 'string') {
        params[key] = stringToBytes(pdfBytes);
      } else if (typeof pdfBytes === 'object' && pdfBytes !== null && !isNaN(pdfBytes.length)) {
        params[key] = new Uint8Array(pdfBytes);
      } else if (isArrayBuffer(pdfBytes)) {
        params[key] = new Uint8Array(pdfBytes);
      } else {
        error('Invalid PDF binary data: either typed array, string or ' + 'array-like object is expected in the data property.');
      }
      continue;
    }
    params[key] = source[key];
  }
  params.rangeChunkSize = params.rangeChunkSize || DEFAULT_RANGE_CHUNK_SIZE;
  params.disableNativeImageDecoder = params.disableNativeImageDecoder === true;
  var CMapReaderFactory = params.CMapReaderFactory || DOMCMapReaderFactory;
  if (!worker) {
    var workerPort = getDefaultSetting('workerPort');
    worker = workerPort ? new PDFWorker(null, workerPort) : new PDFWorker();
    task._worker = worker;
  }
  var docId = task.docId;
  worker.promise.then(function () {
    if (task.destroyed) {
      throw new Error('Loading aborted');
    }
    return _fetchDocument(worker, params, rangeTransport, docId).then(function (workerId) {
      if (task.destroyed) {
        throw new Error('Loading aborted');
      }
      var messageHandler = new MessageHandler(docId, workerId, worker.port);
      var transport = new WorkerTransport(messageHandler, task, rangeTransport, CMapReaderFactory);
      task._transport = transport;
      messageHandler.send('Ready', null);
    });
  }).catch(task._capability.reject);
  return task;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.getFilenameFromUrl"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>getFilenameFromUrl (url)](#apidoc.element.pdfjs-dist.getFilenameFromUrl)
- description and source-code
```javascript
function getFilenameFromUrl(url) {
  var anchor = url.indexOf('#');
  var query = url.indexOf('?');
  var end = Math.min(anchor > 0 ? anchor : url.length, query > 0 ? query : url.length);
  return url.substring(url.lastIndexOf('/', end) + 1, end);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.isValidUrl"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>isValidUrl (url, allowRelative)](#apidoc.element.pdfjs-dist.isValidUrl)
- description and source-code
```javascript
function isValidUrl(url, allowRelative) {
  deprecated('isValidUrl(), please use createValidAbsoluteUrl() instead.');
  var baseUrl = allowRelative ? 'http://example.com' : null;
  return createValidAbsoluteUrl(url, baseUrl) !== null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.removeNullCharacters"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>removeNullCharacters (str)](#apidoc.element.pdfjs-dist.removeNullCharacters)
- description and source-code
```javascript
function removeNullCharacters(str) {
  if (typeof str !== 'string') {
    warn('The argument for removeNullCharacters must be a string.');
    return str;
  }
  return str.replace(NullCharactersRegExp, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.renderTextLayer"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>renderTextLayer (renderParameters)](#apidoc.element.pdfjs-dist.renderTextLayer)
- description and source-code
```javascript
function renderTextLayer(renderParameters) {
  var task = new TextLayerRenderTask(renderParameters.textContent, renderParameters.container, renderParameters.viewport, renderParameters
.textDivs, renderParameters.enhanceTextSelection);
  task._render(renderParameters.timeout);
  return task;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.shadow"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>shadow (obj, prop, value)](#apidoc.element.pdfjs-dist.shadow)
- description and source-code
```javascript
function shadow(obj, prop, value) {
  Object.defineProperty(obj, prop, {
    value: value,
    enumerable: true,
    configurable: true,
    writable: false
  });
  return value;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.AnnotationLayer"></a>[module pdfjs-dist.AnnotationLayer](#apidoc.module.pdfjs-dist.AnnotationLayer)

#### <a name="apidoc.element.pdfjs-dist.AnnotationLayer.render"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.AnnotationLayer.</span>render (parameters)](#apidoc.element.pdfjs-dist.AnnotationLayer.render)
- description and source-code
```javascript
function AnnotationLayer_render(parameters) {
  var annotationElementFactory = new AnnotationElementFactory();
  for (var i = 0, ii = parameters.annotations.length; i < ii; i++) {
    var data = parameters.annotations[i];
    if (!data) {
      continue;
    }
    var element = annotationElementFactory.create({
      data: data,
      layer: parameters.div,
      page: parameters.page,
      viewport: parameters.viewport,
      linkService: parameters.linkService,
      downloadManager: parameters.downloadManager,
      imageResourcesPath: parameters.imageResourcesPath || getDefaultSetting('imageResourcesPath'),
      renderInteractiveForms: parameters.renderInteractiveForms || false
    });
    if (element.isRenderable) {
      parameters.div.appendChild(element.render());
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.AnnotationLayer.update"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.AnnotationLayer.</span>update (parameters)](#apidoc.element.pdfjs-dist.AnnotationLayer.update)
- description and source-code
```javascript
function AnnotationLayer_update(parameters) {
  for (var i = 0, ii = parameters.annotations.length; i < ii; i++) {
    var data = parameters.annotations[i];
    var element = parameters.div.querySelector('[data-annotation-id="' + data.id + '"]');
    if (element) {
      CustomStyle.setProp('transform', element, 'matrix(' + parameters.viewport.transform.join(',') + ')');
    }
  }
  parameters.div.removeAttribute('hidden');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.CustomStyle"></a>[module pdfjs-dist.CustomStyle](#apidoc.module.pdfjs-dist.CustomStyle)

#### <a name="apidoc.element.pdfjs-dist.CustomStyle.CustomStyle"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>CustomStyle ()](#apidoc.element.pdfjs-dist.CustomStyle.CustomStyle)
- description and source-code
```javascript
function CustomStyle() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.CustomStyle.getProp"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.CustomStyle.</span>getProp (propName, element)](#apidoc.element.pdfjs-dist.CustomStyle.getProp)
- description and source-code
```javascript
function get(propName, element) {
  if (arguments.length === 1 && typeof _cache[propName] === 'string') {
    return _cache[propName];
  }
  element = element || document.documentElement;
  var style = element.style,
      prefixed,
      uPropName;
  if (typeof style[propName] === 'string') {
    return _cache[propName] = propName;
  }
  uPropName = propName.charAt(0).toUpperCase() + propName.slice(1);
  for (var i = 0, l = prefixes.length; i < l; i++) {
    prefixed = prefixes[i] + uPropName;
    if (typeof style[prefixed] === 'string') {
      return _cache[propName] = prefixed;
    }
  }
  return _cache[propName] = 'undefined';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.CustomStyle.setProp"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.CustomStyle.</span>setProp (propName, element, str)](#apidoc.element.pdfjs-dist.CustomStyle.setProp)
- description and source-code
```javascript
function set(propName, element, str) {
  var prop = this.getProp(propName);
  if (prop !== 'undefined') {
    element.style[prop] = str;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.InvalidPDFException"></a>[module pdfjs-dist.InvalidPDFException](#apidoc.module.pdfjs-dist.InvalidPDFException)

#### <a name="apidoc.element.pdfjs-dist.InvalidPDFException.InvalidPDFException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>InvalidPDFException (msg)](#apidoc.element.pdfjs-dist.InvalidPDFException.InvalidPDFException)
- description and source-code
```javascript
function InvalidPDFException(msg) {
  this.name = 'InvalidPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.InvalidPDFException.constructor"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.InvalidPDFException.</span>constructor (msg)](#apidoc.element.pdfjs-dist.InvalidPDFException.constructor)
- description and source-code
```javascript
function InvalidPDFException(msg) {
  this.name = 'InvalidPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.MissingPDFException"></a>[module pdfjs-dist.MissingPDFException](#apidoc.module.pdfjs-dist.MissingPDFException)

#### <a name="apidoc.element.pdfjs-dist.MissingPDFException.MissingPDFException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>MissingPDFException (msg)](#apidoc.element.pdfjs-dist.MissingPDFException.MissingPDFException)
- description and source-code
```javascript
function MissingPDFException(msg) {
  this.name = 'MissingPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.MissingPDFException.constructor"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.MissingPDFException.</span>constructor (msg)](#apidoc.element.pdfjs-dist.MissingPDFException.constructor)
- description and source-code
```javascript
function MissingPDFException(msg) {
  this.name = 'MissingPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFDataRangeTransport"></a>[module pdfjs-dist.PDFDataRangeTransport](#apidoc.module.pdfjs-dist.PDFDataRangeTransport)

#### <a name="apidoc.element.pdfjs-dist.PDFDataRangeTransport.PDFDataRangeTransport"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFDataRangeTransport (length, initialData)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.PDFDataRangeTransport)
- description and source-code
```javascript
function PDFDataRangeTransport(length, initialData) {
  this.length = length;
  this.initialData = initialData;
  this._rangeListeners = [];
  this._progressListeners = [];
  this._progressiveReadListeners = [];
  this._readyCapability = createPromiseCapability();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFDataRangeTransport.prototype"></a>[module pdfjs-dist.PDFDataRangeTransport.prototype](#apidoc.module.pdfjs-dist.PDFDataRangeTransport.prototype)

#### <a name="apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.abort"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>abort ()](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.abort)
- description and source-code
```javascript
function PDFDataRangeTransport_abort() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.addProgressListener"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>addProgressListener (listener)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.addProgressListener)
- description and source-code
```javascript
function PDFDataRangeTransport_addProgressListener(listener) {
  this._progressListeners.push(listener);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.addProgressiveReadListener"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>addProgressiveReadListener (listener)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.addProgressiveReadListener)
- description and source-code
```javascript
function PDFDataRangeTransport_addProgressiveReadListener(listener) {
  this._progressiveReadListeners.push(listener);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.addRangeListener"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>addRangeListener (listener)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.addRangeListener)
- description and source-code
```javascript
function PDFDataRangeTransport_addRangeListener(listener) {
  this._rangeListeners.push(listener);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.onDataProgress"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>onDataProgress (loaded)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.onDataProgress)
- description and source-code
```javascript
function PDFDataRangeTransport_onDataProgress(loaded) {
  this._readyCapability.promise.then(function () {
    var listeners = this._progressListeners;
    for (var i = 0, n = listeners.length; i < n; ++i) {
      listeners[i](loaded);
    }
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.onDataProgressiveRead"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>onDataProgressiveRead (chunk)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.onDataProgressiveRead)
- description and source-code
```javascript
function PDFDataRangeTransport_onDataProgress(chunk) {
  this._readyCapability.promise.then(function () {
    var listeners = this._progressiveReadListeners;
    for (var i = 0, n = listeners.length; i < n; ++i) {
      listeners[i](chunk);
    }
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.onDataRange"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>onDataRange (begin, chunk)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.onDataRange)
- description and source-code
```javascript
function PDFDataRangeTransport_onDataRange(begin, chunk) {
  var listeners = this._rangeListeners;
  for (var i = 0, n = listeners.length; i < n; ++i) {
    listeners[i](begin, chunk);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.requestDataRange"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>requestDataRange (begin, end)](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.requestDataRange)
- description and source-code
```javascript
function PDFDataRangeTransport_requestDataRange(begin, end) {
  throw new Error('Abstract method PDFDataRangeTransport.requestDataRange');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.transportReady"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFDataRangeTransport.prototype.</span>transportReady ()](#apidoc.element.pdfjs-dist.PDFDataRangeTransport.prototype.transportReady)
- description and source-code
```javascript
function PDFDataRangeTransport_transportReady() {
  this._readyCapability.resolve();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS"></a>[module pdfjs-dist.PDFJS](#apidoc.module.pdfjs-dist.PDFJS)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.CustomStyle"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>CustomStyle ()](#apidoc.element.pdfjs-dist.PDFJS.CustomStyle)
- description and source-code
```javascript
function CustomStyle() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.InvalidPDFException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>InvalidPDFException (msg)](#apidoc.element.pdfjs-dist.PDFJS.InvalidPDFException)
- description and source-code
```javascript
function InvalidPDFException(msg) {
  this.name = 'InvalidPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Metadata"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>Metadata (meta)](#apidoc.element.pdfjs-dist.PDFJS.Metadata)
- description and source-code
```javascript
function Metadata(meta) {
  if (typeof meta === 'string') {
    meta = fixMetadata(meta);
    var parser = new DOMParser();
    meta = parser.parseFromString(meta, 'application/xml');
  } else if (!(meta instanceof Document)) {
    error('Metadata: Invalid metadata object');
  }
  this.metaDocument = meta;
  this.metadata = Object.create(null);
  this.parse();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.MissingPDFException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>MissingPDFException (msg)](#apidoc.element.pdfjs-dist.PDFJS.MissingPDFException)
- description and source-code
```javascript
function MissingPDFException(msg) {
  this.name = 'MissingPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PDFDataRangeTransport (length, initialData)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport)
- description and source-code
```javascript
function PDFDataRangeTransport(length, initialData) {
  this.length = length;
  this.initialData = initialData;
  this._rangeListeners = [];
  this._progressListeners = [];
  this._progressiveReadListeners = [];
  this._readyCapability = createPromiseCapability();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFWorker"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PDFWorker (name, port)](#apidoc.element.pdfjs-dist.PDFJS.PDFWorker)
- description and source-code
```javascript
function PDFWorker(name, port) {
  this.name = name;
  this.destroyed = false;
  this._readyCapability = createPromiseCapability();
  this._port = null;
  this._webWorker = null;
  this._messageHandler = null;
  if (port) {
    this._initializeFromPort(port);
    return;
  }
  this._initialize();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PageViewport"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PageViewport (viewBox, scale, rotation, offsetX, offsetY, dontFlip)](#apidoc.element.pdfjs-dist.PDFJS.PageViewport)
- description and source-code
```javascript
function PageViewport(viewBox, scale, rotation, offsetX, offsetY, dontFlip) {
  this.viewBox = viewBox;
  this.scale = scale;
  this.rotation = rotation;
  this.offsetX = offsetX;
  this.offsetY = offsetY;
  var centerX = (viewBox[2] + viewBox[0]) / 2;
  var centerY = (viewBox[3] + viewBox[1]) / 2;
  var rotateA, rotateB, rotateC, rotateD;
  rotation = rotation % 360;
  rotation = rotation < 0 ? rotation + 360 : rotation;
  switch (rotation) {
    case 180:
      rotateA = -1;
      rotateB = 0;
      rotateC = 0;
      rotateD = 1;
      break;
    case 90:
      rotateA = 0;
      rotateB = 1;
      rotateC = 1;
      rotateD = 0;
      break;
    case 270:
      rotateA = 0;
      rotateB = -1;
      rotateC = -1;
      rotateD = 0;
      break;
    default:
      rotateA = 1;
      rotateB = 0;
      rotateC = 0;
      rotateD = -1;
      break;
  }
  if (dontFlip) {
    rotateC = -rotateC;
    rotateD = -rotateD;
  }
  var offsetCanvasX, offsetCanvasY;
  var width, height;
  if (rotateA === 0) {
    offsetCanvasX = Math.abs(centerY - viewBox[1]) * scale + offsetX;
    offsetCanvasY = Math.abs(centerX - viewBox[0]) * scale + offsetY;
    width = Math.abs(viewBox[3] - viewBox[1]) * scale;
    height = Math.abs(viewBox[2] - viewBox[0]) * scale;
  } else {
    offsetCanvasX = Math.abs(centerX - viewBox[0]) * scale + offsetX;
    offsetCanvasY = Math.abs(centerY - viewBox[1]) * scale + offsetY;
    width = Math.abs(viewBox[2] - viewBox[0]) * scale;
    height = Math.abs(viewBox[3] - viewBox[1]) * scale;
  }
  this.transform = [rotateA * scale, rotateB * scale, rotateC * scale, rotateD * scale, offsetCanvasX - rotateA * scale * centerX
 - rotateC * scale * centerY, offsetCanvasY - rotateB * scale * centerX - rotateD * scale * centerY];
  this.width = width;
  this.height = height;
  this.fontScale = scale;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PasswordException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PasswordException (msg, code)](#apidoc.element.pdfjs-dist.PDFJS.PasswordException)
- description and source-code
```javascript
function PasswordException(msg, code) {
  this.name = 'PasswordException';
  this.message = msg;
  this.code = code;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>SVGGraphics (commonObjs, objs, forceDataSchema)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics)
- description and source-code
```javascript
function SVGGraphics(commonObjs, objs, forceDataSchema) {
  this.current = new SVGExtraState();
  this.transformMatrix = IDENTITY_MATRIX;
  this.transformStack = [];
  this.extraStack = [];
  this.commonObjs = commonObjs;
  this.objs = objs;
  this.pendingEOFill = false;
  this.embedFonts = false;
  this.embeddedFonts = Object.create(null);
  this.cssStyle = null;
  this.forceDataSchema = !!forceDataSchema;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.UnexpectedResponseException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>UnexpectedResponseException (msg, status)](#apidoc.element.pdfjs-dist.PDFJS.UnexpectedResponseException)
- description and source-code
```javascript
function UnexpectedResponseException(msg, status) {
  this.name = 'UnexpectedResponseException';
  this.message = msg;
  this.status = status;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.UnknownErrorException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>UnknownErrorException (msg, details)](#apidoc.element.pdfjs-dist.PDFJS.UnknownErrorException)
- description and source-code
```javascript
function UnknownErrorException(msg, details) {
  this.name = 'UnknownErrorException';
  this.message = msg;
  this.details = details;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>Util ()](#apidoc.element.pdfjs-dist.PDFJS.Util)
- description and source-code
```javascript
function Util() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.addLinkAttributes"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>addLinkAttributes (link, params)](#apidoc.element.pdfjs-dist.PDFJS.addLinkAttributes)
- description and source-code
```javascript
function addLinkAttributes(link, params) {
  var url = params && params.url;
  link.href = link.title = url ? removeNullCharacters(url) : '';
  if (url) {
    var target = params.target;
    if (typeof target === 'undefined') {
      target = getDefaultSetting('externalLinkTarget');
    }
    link.target = LinkTargetStringMap[target];
    var rel = params.rel;
    if (typeof rel === 'undefined') {
      rel = getDefaultSetting('externalLinkRel');
    }
    link.rel = rel;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.createBlob"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>createBlob (data, contentType)](#apidoc.element.pdfjs-dist.PDFJS.createBlob)
- description and source-code
```javascript
function createBlob(data, contentType) {
  if (typeof Blob !== 'undefined') {
    return new Blob([data], { type: contentType });
  }
  warn('The "Blob" constructor is not supported.');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.createObjectURL"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>createObjectURL (data, contentType)](#apidoc.element.pdfjs-dist.PDFJS.createObjectURL)
- description and source-code
```javascript
function PDFJS_createObjectURL(data, contentType) {
  return sharedUtil.createObjectURL(data, contentType, PDFJS.disableCreateObjectURL);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.createPromiseCapability"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>createPromiseCapability ()](#apidoc.element.pdfjs-dist.PDFJS.createPromiseCapability)
- description and source-code
```javascript
function createPromiseCapability() {
  var capability = {};
  capability.promise = new Promise(function (resolve, reject) {
    capability.resolve = resolve;
    capability.reject = reject;
  });
  return capability;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.getDocument"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>getDocument (src, pdfDataRangeTransport, passwordCallback, progressCallback)](#apidoc.element.pdfjs-dist.PDFJS.getDocument)
- description and source-code
```javascript
function getDocument(src, pdfDataRangeTransport, passwordCallback, progressCallback) {
  var task = new PDFDocumentLoadingTask();
  if (arguments.length > 1) {
    deprecated('getDocument is called with pdfDataRangeTransport, ' + 'passwordCallback or progressCallback argument');
  }
  if (pdfDataRangeTransport) {
    if (!(pdfDataRangeTransport instanceof PDFDataRangeTransport)) {
      pdfDataRangeTransport = Object.create(pdfDataRangeTransport);
      pdfDataRangeTransport.length = src.length;
      pdfDataRangeTransport.initialData = src.initialData;
      if (!pdfDataRangeTransport.abort) {
        pdfDataRangeTransport.abort = function () {};
      }
    }
    src = Object.create(src);
    src.range = pdfDataRangeTransport;
  }
  task.onPassword = passwordCallback || null;
  task.onProgress = progressCallback || null;
  var source;
  if (typeof src === 'string') {
    source = { url: src };
  } else if (isArrayBuffer(src)) {
    source = { data: src };
  } else if (src instanceof PDFDataRangeTransport) {
    source = { range: src };
  } else {
    if (typeof src !== 'object') {
      error('Invalid parameter in getDocument, need either Uint8Array, ' + 'string or a parameter object');
    }
    if (!src.url && !src.data && !src.range) {
      error('Invalid parameter object: need either .data, .range or .url');
    }
    source = src;
  }
  var params = {};
  var rangeTransport = null;
  var worker = null;
  for (var key in source) {
    if (key === 'url' && typeof window !== 'undefined') {
      params[key] = new URL(source[key], window.location).href;
      continue;
    } else if (key === 'range') {
      rangeTransport = source[key];
      continue;
    } else if (key === 'worker') {
      worker = source[key];
      continue;
    } else if (key === 'data' && !(source[key] instanceof Uint8Array)) {
      var pdfBytes = source[key];
      if (typeof pdfBytes === 'string') {
        params[key] = stringToBytes(pdfBytes);
      } else if (typeof pdfBytes === 'object' && pdfBytes !== null && !isNaN(pdfBytes.length)) {
        params[key] = new Uint8Array(pdfBytes);
      } else if (isArrayBuffer(pdfBytes)) {
        params[key] = new Uint8Array(pdfBytes);
      } else {
        error('Invalid PDF binary data: either typed array, string or ' + 'array-like object is expected in the data property.');
      }
      continue;
    }
    params[key] = source[key];
  }
  params.rangeChunkSize = params.rangeChunkSize || DEFAULT_RANGE_CHUNK_SIZE;
  params.disableNativeImageDecoder = params.disableNativeImageDecoder === true;
  var CMapReaderFactory = params.CMapReaderFactory || DOMCMapReaderFactory;
  if (!worker) {
    var workerPort = getDefaultSetting('workerPort');
    worker = workerPort ? new PDFWorker(null, workerPort) : new PDFWorker();
    task._worker = worker;
  }
  var docId = task.docId;
  worker.promise.then(function () {
    if (task.destroyed) {
      throw new Error('Loading aborted');
    }
    return _fetchDocument(worker, params, rangeTransport, docId).then(function (workerId) {
      if (task.destroyed) {
        throw new Error('Loading aborted');
      }
      var messageHandler = new MessageHandler(docId, workerId, worker.port);
      var transport = new WorkerTransport(messageHandler, task, rangeTransport, CMapReaderFactory);
      task._transport = transport;
      messageHandler.send('Ready', null);
    });
  }).catch(task._capability.reject);
  return task;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.getFilenameFromUrl"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>getFilenameFromUrl (url)](#apidoc.element.pdfjs-dist.PDFJS.getFilenameFromUrl)
- description and source-code
```javascript
function getFilenameFromUrl(url) {
  var anchor = url.indexOf('#');
  var query = url.indexOf('?');
  var end = Math.min(anchor > 0 ? anchor : url.length, query > 0 ? query : url.length);
  return url.substring(url.lastIndexOf('/', end) + 1, end);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.isExternalLinkTargetSet"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>isExternalLinkTargetSet ()](#apidoc.element.pdfjs-dist.PDFJS.isExternalLinkTargetSet)
- description and source-code
```javascript
function isExternalLinkTargetSet() {
  var externalLinkTarget = getDefaultSetting('externalLinkTarget');
  switch (externalLinkTarget) {
    case LinkTarget.NONE:
      return false;
    case LinkTarget.SELF:
    case LinkTarget.BLANK:
    case LinkTarget.PARENT:
    case LinkTarget.TOP:
      return true;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.isValidUrl"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>isValidUrl (url, allowRelative)](#apidoc.element.pdfjs-dist.PDFJS.isValidUrl)
- description and source-code
```javascript
function isValidUrl(url, allowRelative) {
  deprecated('isValidUrl(), please use createValidAbsoluteUrl() instead.');
  var baseUrl = allowRelative ? 'http://example.com' : null;
  return createValidAbsoluteUrl(url, baseUrl) !== null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.removeNullCharacters"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>removeNullCharacters (str)](#apidoc.element.pdfjs-dist.PDFJS.removeNullCharacters)
- description and source-code
```javascript
function removeNullCharacters(str) {
  if (typeof str !== 'string') {
    warn('The argument for removeNullCharacters must be a string.');
    return str;
  }
  return str.replace(NullCharactersRegExp, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.renderTextLayer"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>renderTextLayer (renderParameters)](#apidoc.element.pdfjs-dist.PDFJS.renderTextLayer)
- description and source-code
```javascript
function renderTextLayer(renderParameters) {
  var task = new TextLayerRenderTask(renderParameters.textContent, renderParameters.container, renderParameters.viewport, renderParameters
.textDivs, renderParameters.enhanceTextSelection);
  task._render(renderParameters.timeout);
  return task;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.shadow"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>shadow (obj, prop, value)](#apidoc.element.pdfjs-dist.PDFJS.shadow)
- description and source-code
```javascript
function shadow(obj, prop, value) {
  Object.defineProperty(obj, prop, {
    value: value,
    enumerable: true,
    configurable: true,
    writable: false
  });
  return value;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.AnnotationLayer"></a>[module pdfjs-dist.PDFJS.AnnotationLayer](#apidoc.module.pdfjs-dist.PDFJS.AnnotationLayer)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.AnnotationLayer.render"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.AnnotationLayer.</span>render (parameters)](#apidoc.element.pdfjs-dist.PDFJS.AnnotationLayer.render)
- description and source-code
```javascript
function AnnotationLayer_render(parameters) {
  var annotationElementFactory = new AnnotationElementFactory();
  for (var i = 0, ii = parameters.annotations.length; i < ii; i++) {
    var data = parameters.annotations[i];
    if (!data) {
      continue;
    }
    var element = annotationElementFactory.create({
      data: data,
      layer: parameters.div,
      page: parameters.page,
      viewport: parameters.viewport,
      linkService: parameters.linkService,
      downloadManager: parameters.downloadManager,
      imageResourcesPath: parameters.imageResourcesPath || getDefaultSetting('imageResourcesPath'),
      renderInteractiveForms: parameters.renderInteractiveForms || false
    });
    if (element.isRenderable) {
      parameters.div.appendChild(element.render());
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.AnnotationLayer.update"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.AnnotationLayer.</span>update (parameters)](#apidoc.element.pdfjs-dist.PDFJS.AnnotationLayer.update)
- description and source-code
```javascript
function AnnotationLayer_update(parameters) {
  for (var i = 0, ii = parameters.annotations.length; i < ii; i++) {
    var data = parameters.annotations[i];
    var element = parameters.div.querySelector('[data-annotation-id="' + data.id + '"]');
    if (element) {
      CustomStyle.setProp('transform', element, 'matrix(' + parameters.viewport.transform.join(',') + ')');
    }
  }
  parameters.div.removeAttribute('hidden');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.CustomStyle"></a>[module pdfjs-dist.PDFJS.CustomStyle](#apidoc.module.pdfjs-dist.PDFJS.CustomStyle)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.CustomStyle.CustomStyle"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>CustomStyle ()](#apidoc.element.pdfjs-dist.PDFJS.CustomStyle.CustomStyle)
- description and source-code
```javascript
function CustomStyle() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.CustomStyle.getProp"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.CustomStyle.</span>getProp (propName, element)](#apidoc.element.pdfjs-dist.PDFJS.CustomStyle.getProp)
- description and source-code
```javascript
function get(propName, element) {
  if (arguments.length === 1 && typeof _cache[propName] === 'string') {
    return _cache[propName];
  }
  element = element || document.documentElement;
  var style = element.style,
      prefixed,
      uPropName;
  if (typeof style[propName] === 'string') {
    return _cache[propName] = propName;
  }
  uPropName = propName.charAt(0).toUpperCase() + propName.slice(1);
  for (var i = 0, l = prefixes.length; i < l; i++) {
    prefixed = prefixes[i] + uPropName;
    if (typeof style[prefixed] === 'string') {
      return _cache[propName] = prefixed;
    }
  }
  return _cache[propName] = 'undefined';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.CustomStyle.setProp"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.CustomStyle.</span>setProp (propName, element, str)](#apidoc.element.pdfjs-dist.PDFJS.CustomStyle.setProp)
- description and source-code
```javascript
function set(propName, element, str) {
  var prop = this.getProp(propName);
  if (prop !== 'undefined') {
    element.style[prop] = str;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.InvalidPDFException"></a>[module pdfjs-dist.PDFJS.InvalidPDFException](#apidoc.module.pdfjs-dist.PDFJS.InvalidPDFException)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.InvalidPDFException.InvalidPDFException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>InvalidPDFException (msg)](#apidoc.element.pdfjs-dist.PDFJS.InvalidPDFException.InvalidPDFException)
- description and source-code
```javascript
function InvalidPDFException(msg) {
  this.name = 'InvalidPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.InvalidPDFException.constructor"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.InvalidPDFException.</span>constructor (msg)](#apidoc.element.pdfjs-dist.PDFJS.InvalidPDFException.constructor)
- description and source-code
```javascript
function InvalidPDFException(msg) {
  this.name = 'InvalidPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.Metadata"></a>[module pdfjs-dist.PDFJS.Metadata](#apidoc.module.pdfjs-dist.PDFJS.Metadata)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Metadata.Metadata"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>Metadata (meta)](#apidoc.element.pdfjs-dist.PDFJS.Metadata.Metadata)
- description and source-code
```javascript
function Metadata(meta) {
  if (typeof meta === 'string') {
    meta = fixMetadata(meta);
    var parser = new DOMParser();
    meta = parser.parseFromString(meta, 'application/xml');
  } else if (!(meta instanceof Document)) {
    error('Metadata: Invalid metadata object');
  }
  this.metaDocument = meta;
  this.metadata = Object.create(null);
  this.parse();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.Metadata.prototype"></a>[module pdfjs-dist.PDFJS.Metadata.prototype](#apidoc.module.pdfjs-dist.PDFJS.Metadata.prototype)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Metadata.prototype.get"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Metadata.prototype.</span>get (name)](#apidoc.element.pdfjs-dist.PDFJS.Metadata.prototype.get)
- description and source-code
```javascript
function Metadata_get(name) {
  return this.metadata[name] || null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Metadata.prototype.has"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Metadata.prototype.</span>has (name)](#apidoc.element.pdfjs-dist.PDFJS.Metadata.prototype.has)
- description and source-code
```javascript
function Metadata_has(name) {
  return typeof this.metadata[name] !== 'undefined';
}
```
- example usage
```shell
...
  this.id = '$weakmap' + id++;
}
WeakMap.prototype = {
  has: function (obj) {
    return !!Object.getOwnPropertyDescriptor(obj, this.id);
  },
  get: function (obj, defaultValue) {
    return this.has(obj) ? obj[this.id] : defaultValue;
  },
  set: function (obj, value) {
    Object.defineProperty(obj, this.id, {
      value: value,
      enumerable: false,
      configurable: true
    });
...
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Metadata.prototype.parse"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Metadata.prototype.</span>parse ()](#apidoc.element.pdfjs-dist.PDFJS.Metadata.prototype.parse)
- description and source-code
```javascript
function Metadata_parse() {
  var doc = this.metaDocument;
  var rdf = doc.documentElement;
  if (rdf.nodeName.toLowerCase() !== 'rdf:rdf') {
    rdf = rdf.firstChild;
    while (rdf && rdf.nodeName.toLowerCase() !== 'rdf:rdf') {
      rdf = rdf.nextSibling;
    }
  }
  var nodeName = rdf ? rdf.nodeName.toLowerCase() : null;
  if (!rdf || nodeName !== 'rdf:rdf' || !rdf.hasChildNodes()) {
    return;
  }
  var children = rdf.childNodes,
      desc,
      entry,
      name,
      i,
      ii,
      length,
      iLength;
  for (i = 0, length = children.length; i < length; i++) {
    desc = children[i];
    if (desc.nodeName.toLowerCase() !== 'rdf:description') {
      continue;
    }
    for (ii = 0, iLength = desc.childNodes.length; ii < iLength; ii++) {
      if (desc.childNodes[ii].nodeName.toLowerCase() !== '#text') {
        entry = desc.childNodes[ii];
        name = entry.nodeName.toLowerCase();
        this.metadata[name] = entry.textContent.trim();
      }
    }
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.MissingPDFException"></a>[module pdfjs-dist.PDFJS.MissingPDFException](#apidoc.module.pdfjs-dist.PDFJS.MissingPDFException)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.MissingPDFException.MissingPDFException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>MissingPDFException (msg)](#apidoc.element.pdfjs-dist.PDFJS.MissingPDFException.MissingPDFException)
- description and source-code
```javascript
function MissingPDFException(msg) {
  this.name = 'MissingPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.MissingPDFException.constructor"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.MissingPDFException.</span>constructor (msg)](#apidoc.element.pdfjs-dist.PDFJS.MissingPDFException.constructor)
- description and source-code
```javascript
function MissingPDFException(msg) {
  this.name = 'MissingPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.PDFDataRangeTransport"></a>[module pdfjs-dist.PDFJS.PDFDataRangeTransport](#apidoc.module.pdfjs-dist.PDFJS.PDFDataRangeTransport)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.PDFDataRangeTransport"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PDFDataRangeTransport (length, initialData)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.PDFDataRangeTransport)
- description and source-code
```javascript
function PDFDataRangeTransport(length, initialData) {
  this.length = length;
  this.initialData = initialData;
  this._rangeListeners = [];
  this._progressListeners = [];
  this._progressiveReadListeners = [];
  this._readyCapability = createPromiseCapability();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype"></a>[module pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype](#apidoc.module.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.abort"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>abort ()](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.abort)
- description and source-code
```javascript
function PDFDataRangeTransport_abort() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.addProgressListener"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>addProgressListener (listener)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.addProgressListener)
- description and source-code
```javascript
function PDFDataRangeTransport_addProgressListener(listener) {
  this._progressListeners.push(listener);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.addProgressiveReadListener"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>addProgressiveReadListener (listener)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.addProgressiveReadListener)
- description and source-code
```javascript
function PDFDataRangeTransport_addProgressiveReadListener(listener) {
  this._progressiveReadListeners.push(listener);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.addRangeListener"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>addRangeListener (listener)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.addRangeListener)
- description and source-code
```javascript
function PDFDataRangeTransport_addRangeListener(listener) {
  this._rangeListeners.push(listener);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.onDataProgress"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>onDataProgress (loaded)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.onDataProgress)
- description and source-code
```javascript
function PDFDataRangeTransport_onDataProgress(loaded) {
  this._readyCapability.promise.then(function () {
    var listeners = this._progressListeners;
    for (var i = 0, n = listeners.length; i < n; ++i) {
      listeners[i](loaded);
    }
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.onDataProgressiveRead"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>onDataProgressiveRead (chunk)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.onDataProgressiveRead)
- description and source-code
```javascript
function PDFDataRangeTransport_onDataProgress(chunk) {
  this._readyCapability.promise.then(function () {
    var listeners = this._progressiveReadListeners;
    for (var i = 0, n = listeners.length; i < n; ++i) {
      listeners[i](chunk);
    }
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.onDataRange"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>onDataRange (begin, chunk)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.onDataRange)
- description and source-code
```javascript
function PDFDataRangeTransport_onDataRange(begin, chunk) {
  var listeners = this._rangeListeners;
  for (var i = 0, n = listeners.length; i < n; ++i) {
    listeners[i](begin, chunk);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.requestDataRange"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>requestDataRange (begin, end)](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.requestDataRange)
- description and source-code
```javascript
function PDFDataRangeTransport_requestDataRange(begin, end) {
  throw new Error('Abstract method PDFDataRangeTransport.requestDataRange');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.transportReady"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.</span>transportReady ()](#apidoc.element.pdfjs-dist.PDFJS.PDFDataRangeTransport.prototype.transportReady)
- description and source-code
```javascript
function PDFDataRangeTransport_transportReady() {
  this._readyCapability.resolve();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.PDFWorker"></a>[module pdfjs-dist.PDFJS.PDFWorker](#apidoc.module.pdfjs-dist.PDFJS.PDFWorker)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFWorker.PDFWorker"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PDFWorker (name, port)](#apidoc.element.pdfjs-dist.PDFJS.PDFWorker.PDFWorker)
- description and source-code
```javascript
function PDFWorker(name, port) {
  this.name = name;
  this.destroyed = false;
  this._readyCapability = createPromiseCapability();
  this._port = null;
  this._webWorker = null;
  this._messageHandler = null;
  if (port) {
    this._initializeFromPort(port);
    return;
  }
  this._initialize();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.PDFWorker.prototype"></a>[module pdfjs-dist.PDFJS.PDFWorker.prototype](#apidoc.module.pdfjs-dist.PDFJS.PDFWorker.prototype)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFWorker.prototype._initialize"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFWorker.prototype.</span>_initialize ()](#apidoc.element.pdfjs-dist.PDFJS.PDFWorker.prototype._initialize)
- description and source-code
```javascript
function PDFWorker_initialize() {
  if (!isWorkerDisabled && !getDefaultSetting('disableWorker') && typeof Worker !== 'undefined') {
    var workerSrc = getWorkerSrc();
    try {
      if (!isSameOrigin(window.location.href, workerSrc)) {
        workerSrc = createCDNWrapper(new URL(workerSrc, window.location).href);
      }
      var worker = new Worker(workerSrc);
      var messageHandler = new MessageHandler('main', 'worker', worker);
      var terminateEarly = function () {
        worker.removeEventListener('error', onWorkerError);
        messageHandler.destroy();
        worker.terminate();
        if (this.destroyed) {
          this._readyCapability.reject(new Error('Worker was destroyed'));
        } else {
          this._setupFakeWorker();
        }
      }.bind(this);
      var onWorkerError = function (event) {
        if (!this._webWorker) {
          terminateEarly();
        }
      }.bind(this);
      worker.addEventListener('error', onWorkerError);
      messageHandler.on('test', function PDFWorker_test(data) {
        worker.removeEventListener('error', onWorkerError);
        if (this.destroyed) {
          terminateEarly();
          return;
        }
        var supportTypedArray = data && data.supportTypedArray;
        if (supportTypedArray) {
          this._messageHandler = messageHandler;
          this._port = worker;
          this._webWorker = worker;
          if (!data.supportTransfers) {
            isPostMessageTransfersDisabled = true;
          }
          this._readyCapability.resolve();
          messageHandler.send('configure', { verbosity: getVerbosityLevel() });
        } else {
          this._setupFakeWorker();
          messageHandler.destroy();
          worker.terminate();
        }
      }.bind(this));
      messageHandler.on('console_log', function (data) {
        console.log.apply(console, data);
      });
      messageHandler.on('console_error', function (data) {
        console.error.apply(console, data);
      });
      messageHandler.on('ready', function (data) {
        worker.removeEventListener('error', onWorkerError);
        if (this.destroyed) {
          terminateEarly();
          return;
        }
        try {
          sendTest();
        } catch (e) {
          this._setupFakeWorker();
        }
      }.bind(this));
      var sendTest = function () {
        var postMessageTransfers = getDefaultSetting('postMessageTransfers') && !isPostMessageTransfersDisabled;
        var testObj = new Uint8Array([postMessageTransfers ? 255 : 0]);
        try {
          messageHandler.send('test', testObj, [testObj.buffer]);
        } catch (ex) {
          info('Cannot use postMessage transfers');
          testObj[0] = 0;
          messageHandler.send('test', testObj);
        }
      };
      sendTest();
      return;
    } catch (e) {
      info('The worker has been disabled.');
    }
  }
  this._setupFakeWorker();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFWorker.prototype._initializeFromPort"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFWorker.prototype.</span>_initializeFromPort (port)](#apidoc.element.pdfjs-dist.PDFJS.PDFWorker.prototype._initializeFromPort)
- description and source-code
```javascript
function PDFWorker_initializeFromPort(port) {
  this._port = port;
  this._messageHandler = new MessageHandler('main', 'worker', port);
  this._messageHandler.on('ready', function () {});
  this._readyCapability.resolve();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFWorker.prototype._setupFakeWorker"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFWorker.prototype.</span>_setupFakeWorker ()](#apidoc.element.pdfjs-dist.PDFJS.PDFWorker.prototype._setupFakeWorker)
- description and source-code
```javascript
function PDFWorker_setupFakeWorker() {
  if (!isWorkerDisabled && !getDefaultSetting('disableWorker')) {
    warn('Setting up fake worker.');
    isWorkerDisabled = true;
  }
  setupFakeWorkerGlobal().then(function (WorkerMessageHandler) {
    if (this.destroyed) {
      this._readyCapability.reject(new Error('Worker was destroyed'));
      return;
    }
    var isTypedArraysPresent = Uint8Array !== Float32Array;
    var port = new FakeWorkerPort(isTypedArraysPresent);
    this._port = port;
    var id = 'fake' + nextFakeWorkerId++;
    var workerHandler = new MessageHandler(id + '_worker', id, port);
    WorkerMessageHandler.setup(workerHandler, port);
    var messageHandler = new MessageHandler(id, id + '_worker', port);
    this._messageHandler = messageHandler;
    this._readyCapability.resolve();
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PDFWorker.prototype.destroy"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PDFWorker.prototype.</span>destroy ()](#apidoc.element.pdfjs-dist.PDFJS.PDFWorker.prototype.destroy)
- description and source-code
```javascript
function PDFWorker_destroy() {
  this.destroyed = true;
  if (this._webWorker) {
    this._webWorker.terminate();
    this._webWorker = null;
  }
  this._port = null;
  if (this._messageHandler) {
    this._messageHandler.destroy();
    this._messageHandler = null;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.PageViewport"></a>[module pdfjs-dist.PDFJS.PageViewport](#apidoc.module.pdfjs-dist.PDFJS.PageViewport)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PageViewport.PageViewport"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PageViewport (viewBox, scale, rotation, offsetX, offsetY, dontFlip)](#apidoc.element.pdfjs-dist.PDFJS.PageViewport.PageViewport)
- description and source-code
```javascript
function PageViewport(viewBox, scale, rotation, offsetX, offsetY, dontFlip) {
  this.viewBox = viewBox;
  this.scale = scale;
  this.rotation = rotation;
  this.offsetX = offsetX;
  this.offsetY = offsetY;
  var centerX = (viewBox[2] + viewBox[0]) / 2;
  var centerY = (viewBox[3] + viewBox[1]) / 2;
  var rotateA, rotateB, rotateC, rotateD;
  rotation = rotation % 360;
  rotation = rotation < 0 ? rotation + 360 : rotation;
  switch (rotation) {
    case 180:
      rotateA = -1;
      rotateB = 0;
      rotateC = 0;
      rotateD = 1;
      break;
    case 90:
      rotateA = 0;
      rotateB = 1;
      rotateC = 1;
      rotateD = 0;
      break;
    case 270:
      rotateA = 0;
      rotateB = -1;
      rotateC = -1;
      rotateD = 0;
      break;
    default:
      rotateA = 1;
      rotateB = 0;
      rotateC = 0;
      rotateD = -1;
      break;
  }
  if (dontFlip) {
    rotateC = -rotateC;
    rotateD = -rotateD;
  }
  var offsetCanvasX, offsetCanvasY;
  var width, height;
  if (rotateA === 0) {
    offsetCanvasX = Math.abs(centerY - viewBox[1]) * scale + offsetX;
    offsetCanvasY = Math.abs(centerX - viewBox[0]) * scale + offsetY;
    width = Math.abs(viewBox[3] - viewBox[1]) * scale;
    height = Math.abs(viewBox[2] - viewBox[0]) * scale;
  } else {
    offsetCanvasX = Math.abs(centerX - viewBox[0]) * scale + offsetX;
    offsetCanvasY = Math.abs(centerY - viewBox[1]) * scale + offsetY;
    width = Math.abs(viewBox[2] - viewBox[0]) * scale;
    height = Math.abs(viewBox[3] - viewBox[1]) * scale;
  }
  this.transform = [rotateA * scale, rotateB * scale, rotateC * scale, rotateD * scale, offsetCanvasX - rotateA * scale * centerX
 - rotateC * scale * centerY, offsetCanvasY - rotateB * scale * centerX - rotateD * scale * centerY];
  this.width = width;
  this.height = height;
  this.fontScale = scale;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.PageViewport.prototype"></a>[module pdfjs-dist.PDFJS.PageViewport.prototype](#apidoc.module.pdfjs-dist.PDFJS.PageViewport.prototype)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PageViewport.prototype.clone"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PageViewport.prototype.</span>clone (args)](#apidoc.element.pdfjs-dist.PDFJS.PageViewport.prototype.clone)
- description and source-code
```javascript
function PageViewPort_clone(args) {
  args = args || {};
  var scale = 'scale' in args ? args.scale : this.scale;
  var rotation = 'rotation' in args ? args.rotation : this.rotation;
  return new PageViewport(this.viewBox.slice(), scale, rotation, this.offsetX, this.offsetY, args.dontFlip);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PageViewport.prototype.convertToPdfPoint"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PageViewport.prototype.</span>convertToPdfPoint (x, y)](#apidoc.element.pdfjs-dist.PDFJS.PageViewport.prototype.convertToPdfPoint)
- description and source-code
```javascript
function PageViewport_convertToPdfPoint(x, y) {
  return Util.applyInverseTransform([x, y], this.transform);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PageViewport.prototype.convertToViewportPoint"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PageViewport.prototype.</span>convertToViewportPoint (x, y)](#apidoc.element.pdfjs-dist.PDFJS.PageViewport.prototype.convertToViewportPoint)
- description and source-code
```javascript
function PageViewport_convertToViewportPoint(x, y) {
  return Util.applyTransform([x, y], this.transform);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PageViewport.prototype.convertToViewportRectangle"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PageViewport.prototype.</span>convertToViewportRectangle (rect)](#apidoc.element.pdfjs-dist.PDFJS.PageViewport.prototype.convertToViewportRectangle)
- description and source-code
```javascript
function PageViewport_convertToViewportRectangle(rect) {
  var tl = Util.applyTransform([rect[0], rect[1]], this.transform);
  var br = Util.applyTransform([rect[2], rect[3]], this.transform);
  return [tl[0], tl[1], br[0], br[1]];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.PasswordException"></a>[module pdfjs-dist.PDFJS.PasswordException](#apidoc.module.pdfjs-dist.PDFJS.PasswordException)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PasswordException.PasswordException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>PasswordException (msg, code)](#apidoc.element.pdfjs-dist.PDFJS.PasswordException.PasswordException)
- description and source-code
```javascript
function PasswordException(msg, code) {
  this.name = 'PasswordException';
  this.message = msg;
  this.code = code;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.PasswordException.constructor"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.PasswordException.</span>constructor (msg, code)](#apidoc.element.pdfjs-dist.PDFJS.PasswordException.constructor)
- description and source-code
```javascript
function PasswordException(msg, code) {
  this.name = 'PasswordException';
  this.message = msg;
  this.code = code;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.SVGGraphics"></a>[module pdfjs-dist.PDFJS.SVGGraphics](#apidoc.module.pdfjs-dist.PDFJS.SVGGraphics)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.SVGGraphics"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>SVGGraphics (commonObjs, objs, forceDataSchema)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.SVGGraphics)
- description and source-code
```javascript
function SVGGraphics(commonObjs, objs, forceDataSchema) {
  this.current = new SVGExtraState();
  this.transformMatrix = IDENTITY_MATRIX;
  this.transformStack = [];
  this.extraStack = [];
  this.commonObjs = commonObjs;
  this.objs = objs;
  this.pendingEOFill = false;
  this.embedFonts = false;
  this.embeddedFonts = Object.create(null);
  this.cssStyle = null;
  this.forceDataSchema = !!forceDataSchema;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.SVGGraphics.prototype"></a>[module pdfjs-dist.PDFJS.SVGGraphics.prototype](#apidoc.module.pdfjs-dist.PDFJS.SVGGraphics.prototype)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype._ensureClipGroup"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>_ensureClipGroup ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype._ensureClipGroup)
- description and source-code
```javascript
function SVGGraphics_ensureClipGroup() {
  if (!this.current.clipGroup) {
    var clipGroup = document.createElementNS(NS, 'svg:g');
    clipGroup.setAttributeNS(null, 'clip-path', this.current.activeClipUrl);
    this.svg.appendChild(clipGroup);
    this.current.clipGroup = clipGroup;
  }
  return this.current.clipGroup;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype._ensureTransformGroup"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>_ensureTransformGroup ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype._ensureTransformGroup)
- description and source-code
```javascript
function SVGGraphics_ensureTransformGroup() {
  if (!this.tgrp) {
    this.tgrp = document.createElementNS(NS, 'svg:g');
    this.tgrp.setAttributeNS(null, 'transform', pm(this.transformMatrix));
    if (this.current.activeClipUrl) {
      this._ensureClipGroup().appendChild(this.tgrp);
    } else {
      this.svg.appendChild(this.tgrp);
    }
  }
  return this.tgrp;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype._initialize"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>_initialize (viewport)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype._initialize)
- description and source-code
```javascript
function SVGGraphics_initialize(viewport) {
  var svg = document.createElementNS(NS, 'svg:svg');
  svg.setAttributeNS(null, 'version', '1.1');
  svg.setAttributeNS(null, 'width', viewport.width + 'px');
  svg.setAttributeNS(null, 'height', viewport.height + 'px');
  svg.setAttributeNS(null, 'preserveAspectRatio', 'none');
  svg.setAttributeNS(null, 'viewBox', '0 0 ' + viewport.width + ' ' + viewport.height);
  var definitions = document.createElementNS(NS, 'svg:defs');
  svg.appendChild(definitions);
  this.defs = definitions;
  var rootGroup = document.createElementNS(NS, 'svg:g');
  rootGroup.setAttributeNS(null, 'transform', pm(viewport.transform));
  svg.appendChild(rootGroup);
  this.svg = rootGroup;
  return svg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.addFontStyle"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>addFontStyle (fontObj)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.addFontStyle)
- description and source-code
```javascript
function SVGGraphics_addFontStyle(fontObj) {
  if (!this.cssStyle) {
    this.cssStyle = document.createElementNS(NS, 'svg:style');
    this.cssStyle.setAttributeNS(null, 'type', 'text/css');
    this.defs.appendChild(this.cssStyle);
  }
  var url = createObjectURL(fontObj.data, fontObj.mimetype, this.forceDataSchema);
  this.cssStyle.textContent += '@font-face { font-family: "' + fontObj.loadedName + '";' + ' src: url(' + url + '); }\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.beginText"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>beginText ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.beginText)
- description and source-code
```javascript
function SVGGraphics_beginText() {
  this.current.x = this.current.lineX = 0;
  this.current.y = this.current.lineY = 0;
  this.current.textMatrix = IDENTITY_MATRIX;
  this.current.lineMatrix = IDENTITY_MATRIX;
  this.current.tspan = document.createElementNS(NS, 'svg:tspan');
  this.current.txtElement = document.createElementNS(NS, 'svg:text');
  this.current.txtgrp = document.createElementNS(NS, 'svg:g');
  this.current.xcoords = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.clip"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>clip (type)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.clip)
- description and source-code
```javascript
function SVGGraphics_clip(type) {
  var current = this.current;
  var clipId = 'clippath' + clipCount;
  clipCount++;
  var clipPath = document.createElementNS(NS, 'svg:clipPath');
  clipPath.setAttributeNS(null, 'id', clipId);
  clipPath.setAttributeNS(null, 'transform', pm(this.transformMatrix));
  var clipElement = current.element.cloneNode();
  if (type === 'evenodd') {
    clipElement.setAttributeNS(null, 'clip-rule', 'evenodd');
  } else {
    clipElement.setAttributeNS(null, 'clip-rule', 'nonzero');
  }
  clipPath.appendChild(clipElement);
  this.defs.appendChild(clipPath);
  if (current.activeClipUrl) {
    current.clipGroup = null;
    this.extraStack.forEach(function (prev) {
      prev.clipGroup = null;
    });
  }
  current.activeClipUrl = 'url(#' + clipId + ')';
  this.tgrp = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.closeFillStroke"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>closeFillStroke ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.closeFillStroke)
- description and source-code
```javascript
function SVGGraphics_closeFillStroke() {
  this.closePath();
  this.fillStroke();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.closePath"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>closePath ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.closePath)
- description and source-code
```javascript
function SVGGraphics_closePath() {
  var current = this.current;
  var d = current.path.getAttributeNS(null, 'd');
  d += 'Z';
  current.path.setAttributeNS(null, 'd', d);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.closeStroke"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>closeStroke ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.closeStroke)
- description and source-code
```javascript
function SVGGraphics_closeStroke() {
  this.closePath();
  this.stroke();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.constructPath"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>constructPath (ops, args)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.constructPath)
- description and source-code
```javascript
function SVGGraphics_constructPath(ops, args) {
  var current = this.current;
  var x = current.x,
      y = current.y;
  current.path = document.createElementNS(NS, 'svg:path');
  var d = [];
  var opLength = ops.length;
  for (var i = 0, j = 0; i < opLength; i++) {
    switch (ops[i] | 0) {
      case OPS.rectangle:
        x = args[j++];
        y = args[j++];
        var width = args[j++];
        var height = args[j++];
        var xw = x + width;
        var yh = y + height;
        d.push('M', pf(x), pf(y), 'L', pf(xw), pf(y), 'L', pf(xw), pf(yh), 'L', pf(x), pf(yh), 'Z');
        break;
      case OPS.moveTo:
        x = args[j++];
        y = args[j++];
        d.push('M', pf(x), pf(y));
        break;
      case OPS.lineTo:
        x = args[j++];
        y = args[j++];
        d.push('L', pf(x), pf(y));
        break;
      case OPS.curveTo:
        x = args[j + 4];
        y = args[j + 5];
        d.push('C', pf(args[j]), pf(args[j + 1]), pf(args[j + 2]), pf(args[j + 3]), pf(x), pf(y));
        j += 6;
        break;
      case OPS.curveTo2:
        x = args[j + 2];
        y = args[j + 3];
        d.push('C', pf(x), pf(y), pf(args[j]), pf(args[j + 1]), pf(args[j + 2]), pf(args[j + 3]));
        j += 4;
        break;
      case OPS.curveTo3:
        x = args[j + 2];
        y = args[j + 3];
        d.push('C', pf(args[j]), pf(args[j + 1]), pf(x), pf(y), pf(x), pf(y));
        j += 4;
        break;
      case OPS.closePath:
        d.push('Z');
        break;
    }
  }
  current.path.setAttributeNS(null, 'd', d.join(' '));
  current.path.setAttributeNS(null, 'stroke-miterlimit', pf(current.miterLimit));
  current.path.setAttributeNS(null, 'stroke-linecap', current.lineCap);
  current.path.setAttributeNS(null, 'stroke-linejoin', current.lineJoin);
  current.path.setAttributeNS(null, 'stroke-width', pf(current.lineWidth) + 'px');
  current.path.setAttributeNS(null, 'stroke-dasharray', current.dashArray.map(pf).join(' '));
  current.path.setAttributeNS(null, 'stroke-dashoffset', pf(current.dashPhase) + 'px');
  current.path.setAttributeNS(null, 'fill', 'none');
  this._ensureTransformGroup().appendChild(current.path);
  current.element = current.path;
  current.setCurrentPoint(x, y);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.convertOpList"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>convertOpList (operatorList)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.convertOpList)
- description and source-code
```javascript
function SVGGraphics_convertOpList(operatorList) {
  var argsArray = operatorList.argsArray;
  var fnArray = operatorList.fnArray;
  var fnArrayLen = fnArray.length;
  var REVOPS = [];
  var opList = [];
  for (var op in OPS) {
    REVOPS[OPS[op]] = op;
  }
  for (var x = 0; x < fnArrayLen; x++) {
    var fnId = fnArray[x];
    opList.push({
      'fnId': fnId,
      'fn': REVOPS[fnId],
      'args': argsArray[x]
    });
  }
  return opListToTree(opList);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.endPath"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>endPath ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.endPath)
- description and source-code
```javascript
function SVGGraphics_endPath() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.endText"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>endText ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.endText)
- description and source-code
```javascript
function SVGGraphics_endText() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.eoFill"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>eoFill ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.eoFill)
- description and source-code
```javascript
function SVGGraphics_eoFill() {
  var current = this.current;
  current.element.setAttributeNS(null, 'fill', current.fillColor);
  current.element.setAttributeNS(null, 'fill-rule', 'evenodd');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.eoFillStroke"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>eoFillStroke ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.eoFillStroke)
- description and source-code
```javascript
function SVGGraphics_eoFillStroke() {
  this.current.element.setAttributeNS(null, 'fill-rule', 'evenodd');
  this.fillStroke();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.executeOpTree"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>executeOpTree (opTree)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.executeOpTree)
- description and source-code
```javascript
function SVGGraphics_executeOpTree(opTree) {
  var opTreeLen = opTree.length;
  for (var x = 0; x < opTreeLen; x++) {
    var fn = opTree[x].fn;
    var fnId = opTree[x].fnId;
    var args = opTree[x].args;
    switch (fnId | 0) {
      case OPS.beginText:
        this.beginText();
        break;
      case OPS.setLeading:
        this.setLeading(args);
        break;
      case OPS.setLeadingMoveText:
        this.setLeadingMoveText(args[0], args[1]);
        break;
      case OPS.setFont:
        this.setFont(args);
        break;
      case OPS.showText:
        this.showText(args[0]);
        break;
      case OPS.showSpacedText:
        this.showText(args[0]);
        break;
      case OPS.endText:
        this.endText();
        break;
      case OPS.moveText:
        this.moveText(args[0], args[1]);
        break;
      case OPS.setCharSpacing:
        this.setCharSpacing(args[0]);
        break;
      case OPS.setWordSpacing:
        this.setWordSpacing(args[0]);
        break;
      case OPS.setHScale:
        this.setHScale(args[0]);
        break;
      case OPS.setTextMatrix:
        this.setTextMatrix(args[0], args[1], args[2], args[3], args[4], args[5]);
        break;
      case OPS.setLineWidth:
        this.setLineWidth(args[0]);
        break;
      case OPS.setLineJoin:
        this.setLineJoin(args[0]);
        break;
      case OPS.setLineCap:
        this.setLineCap(args[0]);
        break;
      case OPS.setMiterLimit:
        this.setMiterLimit(args[0]);
        break;
      case OPS.setFillRGBColor:
        this.setFillRGBColor(args[0], args[1], args[2]);
        break;
      case OPS.setStrokeRGBColor:
        this.setStrokeRGBColor(args[0], args[1], args[2]);
        break;
      case OPS.setDash:
        this.setDash(args[0], args[1]);
        break;
      case OPS.setGState:
        this.setGState(args[0]);
        break;
      case OPS.fill:
        this.fill();
        break;
      case OPS.eoFill:
        this.eoFill();
        break;
      case OPS.stroke:
        this.stroke();
        break;
      case OPS.fillStroke:
        this.fillStroke();
        break;
      case OPS.eoFillStroke:
        this.eoFillStroke();
        break;
      case OPS.clip:
        this.clip('nonzero');
        break;
      case OPS.eoClip:
        this.clip('evenodd');
        break;
      case OPS.paintSolidColorImageMask:
        this.paintSolidColorImageMask();
        break;
      case OPS.paintJpegXObject:
        this.paintJpegXObject(args[0], args[1], args[2]);
        break;
      case OPS.paintImageXObject:
        this.paintImageXObject(args[0]);
        break;
      case OPS.paintInlineImageXObject:
        this.paintInlineImageXObject(args[0]);
        break;
      case OPS.paintImageMaskXObject:
        this.paintImageMaskXObject(args[0]);
        break;
      case OPS.paintFormXObjectBegin:
        this.paintFormXObjectBegin(args[0], args[1]);
        break;
      case OPS.paintFormXObjectEnd:
        this.paintFormXObjectEnd();
        break;
      case OPS.closePath:
        this.closePath();
        break;
      case OPS.closeStroke:
        this.closeStroke();
        break;
      case OPS.closeFillStroke:
        this.closeFillStroke();
        break;
      case OPS.nextLine:
        this.nextLine();
        break;
      case OPS.transform:
        this.transform(args[0], args[1], args[2], args[3], args[4], args[5]);
        break;
      case OPS.constructPath:
        this.constructPath(args[0], args[1]);
        break;
      case OPS.endPath:
        this.endPath();
        break;
      case 92:
        this.group(opTree[x].items);
        break;
      default:
        warn('Unimplemented operator ' + fn);
        break;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.fill"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>fill ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.fill)
- description and source-code
```javascript
function SVGGraphics_fill() {
  var current = this.current;
  current.element.setAttributeNS(null, 'fill', current.fillColor);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.fillStroke"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>fillStroke ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.fillStroke)
- description and source-code
```javascript
function SVGGraphics_fillStroke() {
  this.stroke();
  this.fill();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.getSVG"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>getSVG (operatorList, viewport)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.getSVG)
- description and source-code
```javascript
function SVGGraphics_getSVG(operatorList, viewport) {
  this.viewport = viewport;
  var svgElement = this._initialize(viewport);
  return this.loadDependencies(operatorList).then(function () {
    this.transformMatrix = IDENTITY_MATRIX;
    var opTree = this.convertOpList(operatorList);
    this.executeOpTree(opTree);
    return svgElement;
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.group"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>group (items)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.group)
- description and source-code
```javascript
function SVGGraphics_group(items) {
  this.save();
  this.executeOpTree(items);
  this.restore();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.loadDependencies"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>loadDependencies (operatorList)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.loadDependencies)
- description and source-code
```javascript
function SVGGraphics_loadDependencies(operatorList) {
  var fnArray = operatorList.fnArray;
  var fnArrayLen = fnArray.length;
  var argsArray = operatorList.argsArray;
  var self = this;
  for (var i = 0; i < fnArrayLen; i++) {
    if (OPS.dependency === fnArray[i]) {
      var deps = argsArray[i];
      for (var n = 0, nn = deps.length; n < nn; n++) {
        var obj = deps[n];
        var common = obj.substring(0, 2) === 'g_';
        var promise;
        if (common) {
          promise = new Promise(function (resolve) {
            self.commonObjs.get(obj, resolve);
          });
        } else {
          promise = new Promise(function (resolve) {
            self.objs.get(obj, resolve);
          });
        }
        this.current.dependencies.push(promise);
      }
    }
  }
  return Promise.all(this.current.dependencies);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.moveText"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>moveText (x, y)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.moveText)
- description and source-code
```javascript
function SVGGraphics_moveText(x, y) {
  var current = this.current;
  this.current.x = this.current.lineX += x;
  this.current.y = this.current.lineY += y;
  current.xcoords = [];
  current.tspan = document.createElementNS(NS, 'svg:tspan');
  current.tspan.setAttributeNS(null, 'font-family', current.fontFamily);
  current.tspan.setAttributeNS(null, 'font-size', pf(current.fontSize) + 'px');
  current.tspan.setAttributeNS(null, 'y', pf(-current.y));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.nextLine"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>nextLine ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.nextLine)
- description and source-code
```javascript
function SVGGraphics_nextLine() {
  this.moveText(0, this.current.leading);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintFormXObjectBegin"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>paintFormXObjectBegin (matrix, bbox)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintFormXObjectBegin)
- description and source-code
```javascript
function SVGGraphics_paintFormXObjectBegin(matrix, bbox) {
  if (isArray(matrix) && matrix.length === 6) {
    this.transform(matrix[0], matrix[1], matrix[2], matrix[3], matrix[4], matrix[5]);
  }
  if (isArray(bbox) && bbox.length === 4) {
    var width = bbox[2] - bbox[0];
    var height = bbox[3] - bbox[1];
    var cliprect = document.createElementNS(NS, 'svg:rect');
    cliprect.setAttributeNS(null, 'x', bbox[0]);
    cliprect.setAttributeNS(null, 'y', bbox[1]);
    cliprect.setAttributeNS(null, 'width', pf(width));
    cliprect.setAttributeNS(null, 'height', pf(height));
    this.current.element = cliprect;
    this.clip('nonzero');
    this.endPath();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintFormXObjectEnd"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>paintFormXObjectEnd ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintFormXObjectEnd)
- description and source-code
```javascript
function SVGGraphics_paintFormXObjectEnd() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintImageMaskXObject"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>paintImageMaskXObject (imgData)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintImageMaskXObject)
- description and source-code
```javascript
function SVGGraphics_paintImageMaskXObject(imgData) {
  var current = this.current;
  var width = imgData.width;
  var height = imgData.height;
  var fillColor = current.fillColor;
  current.maskId = 'mask' + maskCount++;
  var mask = document.createElementNS(NS, 'svg:mask');
  mask.setAttributeNS(null, 'id', current.maskId);
  var rect = document.createElementNS(NS, 'svg:rect');
  rect.setAttributeNS(null, 'x', '0');
  rect.setAttributeNS(null, 'y', '0');
  rect.setAttributeNS(null, 'width', pf(width));
  rect.setAttributeNS(null, 'height', pf(height));
  rect.setAttributeNS(null, 'fill', fillColor);
  rect.setAttributeNS(null, 'mask', 'url(#' + current.maskId + ')');
  this.defs.appendChild(mask);
  this._ensureTransformGroup().appendChild(rect);
  this.paintInlineImageXObject(imgData, mask);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintImageXObject"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>paintImageXObject (objId)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintImageXObject)
- description and source-code
```javascript
function SVGGraphics_paintImageXObject(objId) {
  var imgData = this.objs.get(objId);
  if (!imgData) {
    warn('Dependent image isn\'t ready yet');
    return;
  }
  this.paintInlineImageXObject(imgData);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintInlineImageXObject"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>paintInlineImageXObject (imgData, mask)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintInlineImageXObject)
- description and source-code
```javascript
function SVGGraphics_paintInlineImageXObject(imgData, mask) {
  var width = imgData.width;
  var height = imgData.height;
  var imgSrc = convertImgDataToPng(imgData, this.forceDataSchema);
  var cliprect = document.createElementNS(NS, 'svg:rect');
  cliprect.setAttributeNS(null, 'x', '0');
  cliprect.setAttributeNS(null, 'y', '0');
  cliprect.setAttributeNS(null, 'width', pf(width));
  cliprect.setAttributeNS(null, 'height', pf(height));
  this.current.element = cliprect;
  this.clip('nonzero');
  var imgEl = document.createElementNS(NS, 'svg:image');
  imgEl.setAttributeNS(XLINK_NS, 'xlink:href', imgSrc);
  imgEl.setAttributeNS(null, 'x', '0');
  imgEl.setAttributeNS(null, 'y', pf(-height));
  imgEl.setAttributeNS(null, 'width', pf(width) + 'px');
  imgEl.setAttributeNS(null, 'height', pf(height) + 'px');
  imgEl.setAttributeNS(null, 'transform', 'scale(' + pf(1 / width) + ' ' + pf(-1 / height) + ')');
  if (mask) {
    mask.appendChild(imgEl);
  } else {
    this._ensureTransformGroup().appendChild(imgEl);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintJpegXObject"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>paintJpegXObject (objId, w, h)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintJpegXObject)
- description and source-code
```javascript
function SVGGraphics_paintJpegXObject(objId, w, h) {
  var imgObj = this.objs.get(objId);
  var imgEl = document.createElementNS(NS, 'svg:image');
  imgEl.setAttributeNS(XLINK_NS, 'xlink:href', imgObj.src);
  imgEl.setAttributeNS(null, 'width', imgObj.width + 'px');
  imgEl.setAttributeNS(null, 'height', imgObj.height + 'px');
  imgEl.setAttributeNS(null, 'x', '0');
  imgEl.setAttributeNS(null, 'y', pf(-h));
  imgEl.setAttributeNS(null, 'transform', 'scale(' + pf(1 / w) + ' ' + pf(-1 / h) + ')');
  this._ensureTransformGroup().appendChild(imgEl);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintSolidColorImageMask"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>paintSolidColorImageMask ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.paintSolidColorImageMask)
- description and source-code
```javascript
function SVGGraphics_paintSolidColorImageMask() {
  var current = this.current;
  var rect = document.createElementNS(NS, 'svg:rect');
  rect.setAttributeNS(null, 'x', '0');
  rect.setAttributeNS(null, 'y', '0');
  rect.setAttributeNS(null, 'width', '1px');
  rect.setAttributeNS(null, 'height', '1px');
  rect.setAttributeNS(null, 'fill', current.fillColor);
  this._ensureTransformGroup().appendChild(rect);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.restore"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>restore ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.restore)
- description and source-code
```javascript
function SVGGraphics_restore() {
  this.transformMatrix = this.transformStack.pop();
  this.current = this.extraStack.pop();
  this.tgrp = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.save"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>save ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.save)
- description and source-code
```javascript
function SVGGraphics_save() {
  this.transformStack.push(this.transformMatrix);
  var old = this.current;
  this.extraStack.push(old);
  this.current = old.clone();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setCharSpacing"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setCharSpacing (charSpacing)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setCharSpacing)
- description and source-code
```javascript
function SVGGraphics_setCharSpacing(charSpacing) {
  this.current.charSpacing = charSpacing;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setDash"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setDash (dashArray, dashPhase)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setDash)
- description and source-code
```javascript
function SVGGraphics_setDash(dashArray, dashPhase) {
  this.current.dashArray = dashArray;
  this.current.dashPhase = dashPhase;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setFillRGBColor"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setFillRGBColor (r, g, b)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setFillRGBColor)
- description and source-code
```javascript
function SVGGraphics_setFillRGBColor(r, g, b) {
  var color = Util.makeCssRgb(r, g, b);
  this.current.fillColor = color;
  this.current.tspan = document.createElementNS(NS, 'svg:tspan');
  this.current.xcoords = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setFont"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setFont (details)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setFont)
- description and source-code
```javascript
function SVGGraphics_setFont(details) {
  var current = this.current;
  var fontObj = this.commonObjs.get(details[0]);
  var size = details[1];
  this.current.font = fontObj;
  if (this.embedFonts && fontObj.data && !this.embeddedFonts[fontObj.loadedName]) {
    this.addFontStyle(fontObj);
    this.embeddedFonts[fontObj.loadedName] = fontObj;
  }
  current.fontMatrix = fontObj.fontMatrix ? fontObj.fontMatrix : FONT_IDENTITY_MATRIX;
  var bold = fontObj.black ? fontObj.bold ? 'bolder' : 'bold' : fontObj.bold ? 'bold' : 'normal';
  var italic = fontObj.italic ? 'italic' : 'normal';
  if (size < 0) {
    size = -size;
    current.fontDirection = -1;
  } else {
    current.fontDirection = 1;
  }
  current.fontSize = size;
  current.fontFamily = fontObj.loadedName;
  current.fontWeight = bold;
  current.fontStyle = italic;
  current.tspan = document.createElementNS(NS, 'svg:tspan');
  current.tspan.setAttributeNS(null, 'y', pf(-current.y));
  current.xcoords = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setGState"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setGState (states)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setGState)
- description and source-code
```javascript
function SVGGraphics_setGState(states) {
  for (var i = 0, ii = states.length; i < ii; i++) {
    var state = states[i];
    var key = state[0];
    var value = state[1];
    switch (key) {
      case 'LW':
        this.setLineWidth(value);
        break;
      case 'LC':
        this.setLineCap(value);
        break;
      case 'LJ':
        this.setLineJoin(value);
        break;
      case 'ML':
        this.setMiterLimit(value);
        break;
      case 'D':
        this.setDash(value[0], value[1]);
        break;
      case 'Font':
        this.setFont(value);
        break;
      default:
        warn('Unimplemented graphic state ' + key);
        break;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setHScale"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setHScale (scale)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setHScale)
- description and source-code
```javascript
function SVGGraphics_setHScale(scale) {
  this.current.textHScale = scale / 100;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setLeading"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setLeading (leading)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setLeading)
- description and source-code
```javascript
function SVGGraphics_setLeading(leading) {
  this.current.leading = -leading;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setLeadingMoveText"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setLeadingMoveText (x, y)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setLeadingMoveText)
- description and source-code
```javascript
function SVGGraphics_setLeadingMoveText(x, y) {
  this.setLeading(-y);
  this.moveText(x, y);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setLineCap"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setLineCap (style)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setLineCap)
- description and source-code
```javascript
function SVGGraphics_setLineCap(style) {
  this.current.lineCap = LINE_CAP_STYLES[style];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setLineJoin"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setLineJoin (style)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setLineJoin)
- description and source-code
```javascript
function SVGGraphics_setLineJoin(style) {
  this.current.lineJoin = LINE_JOIN_STYLES[style];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setLineWidth"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setLineWidth (width)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setLineWidth)
- description and source-code
```javascript
function SVGGraphics_setLineWidth(width) {
  this.current.lineWidth = width;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setMiterLimit"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setMiterLimit (limit)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setMiterLimit)
- description and source-code
```javascript
function SVGGraphics_setMiterLimit(limit) {
  this.current.miterLimit = limit;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setStrokeRGBColor"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setStrokeRGBColor (r, g, b)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setStrokeRGBColor)
- description and source-code
```javascript
function SVGGraphics_setStrokeRGBColor(r, g, b) {
  var color = Util.makeCssRgb(r, g, b);
  this.current.strokeColor = color;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setTextMatrix"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setTextMatrix (a, b, c, d, e, f)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setTextMatrix)
- description and source-code
```javascript
function SVGGraphics_setTextMatrix(a, b, c, d, e, f) {
  var current = this.current;
  this.current.textMatrix = this.current.lineMatrix = [a, b, c, d, e, f];
  this.current.x = this.current.lineX = 0;
  this.current.y = this.current.lineY = 0;
  current.xcoords = [];
  current.tspan = document.createElementNS(NS, 'svg:tspan');
  current.tspan.setAttributeNS(null, 'font-family', current.fontFamily);
  current.tspan.setAttributeNS(null, 'font-size', pf(current.fontSize) + 'px');
  current.tspan.setAttributeNS(null, 'y', pf(-current.y));
  current.txtElement = document.createElementNS(NS, 'svg:text');
  current.txtElement.appendChild(current.tspan);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setTextRise"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setTextRise (textRise)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setTextRise)
- description and source-code
```javascript
function SVGGraphics_setTextRise(textRise) {
  this.current.textRise = textRise;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setWordSpacing"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>setWordSpacing (wordSpacing)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.setWordSpacing)
- description and source-code
```javascript
function SVGGraphics_setWordSpacing(wordSpacing) {
  this.current.wordSpacing = wordSpacing;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.showText"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>showText (glyphs)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.showText)
- description and source-code
```javascript
function SVGGraphics_showText(glyphs) {
  var current = this.current;
  var font = current.font;
  var fontSize = current.fontSize;
  if (fontSize === 0) {
    return;
  }
  var charSpacing = current.charSpacing;
  var wordSpacing = current.wordSpacing;
  var fontDirection = current.fontDirection;
  var textHScale = current.textHScale * fontDirection;
  var glyphsLength = glyphs.length;
  var vertical = font.vertical;
  var widthAdvanceScale = fontSize * current.fontMatrix[0];
  var x = 0,
      i;
  for (i = 0; i < glyphsLength; ++i) {
    var glyph = glyphs[i];
    if (glyph === null) {
      x += fontDirection * wordSpacing;
      continue;
    } else if (isNum(glyph)) {
      x += -glyph * fontSize * 0.001;
      continue;
    }
    current.xcoords.push(current.x + x * textHScale);
    var width = glyph.width;
    var character = glyph.fontChar;
    var charWidth = width * widthAdvanceScale + charSpacing * fontDirection;
    x += charWidth;
    current.tspan.textContent += character;
  }
  if (vertical) {
    current.y -= x * textHScale;
  } else {
    current.x += x * textHScale;
  }
  current.tspan.setAttributeNS(null, 'x', current.xcoords.map(pf).join(' '));
  current.tspan.setAttributeNS(null, 'y', pf(-current.y));
  current.tspan.setAttributeNS(null, 'font-family', current.fontFamily);
  current.tspan.setAttributeNS(null, 'font-size', pf(current.fontSize) + 'px');
  if (current.fontStyle !== SVG_DEFAULTS.fontStyle) {
    current.tspan.setAttributeNS(null, 'font-style', current.fontStyle);
  }
  if (current.fontWeight !== SVG_DEFAULTS.fontWeight) {
    current.tspan.setAttributeNS(null, 'font-weight', current.fontWeight);
  }
  if (current.fillColor !== SVG_DEFAULTS.fillColor) {
    current.tspan.setAttributeNS(null, 'fill', current.fillColor);
  }
  current.txtElement.setAttributeNS(null, 'transform', pm(current.textMatrix) + ' scale(1, -1)');
  current.txtElement.setAttributeNS(XML_NS, 'xml:space', 'preserve');
  current.txtElement.appendChild(current.tspan);
  current.txtgrp.appendChild(current.txtElement);
  this._ensureTransformGroup().appendChild(current.txtElement);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.stroke"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>stroke ()](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.stroke)
- description and source-code
```javascript
function SVGGraphics_stroke() {
  var current = this.current;
  current.element.setAttributeNS(null, 'stroke', current.strokeColor);
  current.element.setAttributeNS(null, 'fill', 'none');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.transform"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.SVGGraphics.prototype.</span>transform (a, b, c, d, e, f)](#apidoc.element.pdfjs-dist.PDFJS.SVGGraphics.prototype.transform)
- description and source-code
```javascript
function SVGGraphics_transform(a, b, c, d, e, f) {
  var transformMatrix = [a, b, c, d, e, f];
  this.transformMatrix = Util.transform(this.transformMatrix, transformMatrix);
  this.tgrp = null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.UnexpectedResponseException"></a>[module pdfjs-dist.PDFJS.UnexpectedResponseException](#apidoc.module.pdfjs-dist.PDFJS.UnexpectedResponseException)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.UnexpectedResponseException.UnexpectedResponseException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>UnexpectedResponseException (msg, status)](#apidoc.element.pdfjs-dist.PDFJS.UnexpectedResponseException.UnexpectedResponseException)
- description and source-code
```javascript
function UnexpectedResponseException(msg, status) {
  this.name = 'UnexpectedResponseException';
  this.message = msg;
  this.status = status;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.UnexpectedResponseException.constructor"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.UnexpectedResponseException.</span>constructor (msg, status)](#apidoc.element.pdfjs-dist.PDFJS.UnexpectedResponseException.constructor)
- description and source-code
```javascript
function UnexpectedResponseException(msg, status) {
  this.name = 'UnexpectedResponseException';
  this.message = msg;
  this.status = status;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.UnknownErrorException"></a>[module pdfjs-dist.PDFJS.UnknownErrorException](#apidoc.module.pdfjs-dist.PDFJS.UnknownErrorException)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.UnknownErrorException.UnknownErrorException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>UnknownErrorException (msg, details)](#apidoc.element.pdfjs-dist.PDFJS.UnknownErrorException.UnknownErrorException)
- description and source-code
```javascript
function UnknownErrorException(msg, details) {
  this.name = 'UnknownErrorException';
  this.message = msg;
  this.details = details;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.UnknownErrorException.constructor"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.UnknownErrorException.</span>constructor (msg, details)](#apidoc.element.pdfjs-dist.PDFJS.UnknownErrorException.constructor)
- description and source-code
```javascript
function UnknownErrorException(msg, details) {
  this.name = 'UnknownErrorException';
  this.message = msg;
  this.details = details;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.UnsupportedManager"></a>[module pdfjs-dist.PDFJS.UnsupportedManager](#apidoc.module.pdfjs-dist.PDFJS.UnsupportedManager)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.UnsupportedManager.listen"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.UnsupportedManager.</span>listen (cb)](#apidoc.element.pdfjs-dist.PDFJS.UnsupportedManager.listen)
- description and source-code
```javascript
listen = function (cb) {
  deprecated('Global UnsupportedManager.listen is used: ' + ' use PDFDocumentLoadingTask.onUnsupportedFeature instead');
  listeners.push(cb);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.UnsupportedManager.notify"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.UnsupportedManager.</span>notify (featureId)](#apidoc.element.pdfjs-dist.PDFJS.UnsupportedManager.notify)
- description and source-code
```javascript
notify = function (featureId) {
  for (var i = 0, ii = listeners.length; i < ii; i++) {
    listeners[i](featureId);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFJS.Util"></a>[module pdfjs-dist.PDFJS.Util](#apidoc.module.pdfjs-dist.PDFJS.Util)

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.Util"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.</span>Util ()](#apidoc.element.pdfjs-dist.PDFJS.Util.Util)
- description and source-code
```javascript
function Util() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.appendToArray"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>appendToArray (arr1, arr2)](#apidoc.element.pdfjs-dist.PDFJS.Util.appendToArray)
- description and source-code
```javascript
function Util_appendToArray(arr1, arr2) {
  Array.prototype.push.apply(arr1, arr2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.apply3dTransform"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>apply3dTransform (m, v)](#apidoc.element.pdfjs-dist.PDFJS.Util.apply3dTransform)
- description and source-code
```javascript
function Util_apply3dTransform(m, v) {
  return [m[0] * v[0] + m[1] * v[1] + m[2] * v[2], m[3] * v[0] + m[4] * v[1] + m[5] * v[2], m[6] * v[0] + m[7] * v[1] + m[8] * v
[2]];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.applyInverseTransform"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>applyInverseTransform (p, m)](#apidoc.element.pdfjs-dist.PDFJS.Util.applyInverseTransform)
- description and source-code
```javascript
function Util_applyInverseTransform(p, m) {
  var d = m[0] * m[3] - m[1] * m[2];
  var xt = (p[0] * m[3] - p[1] * m[2] + m[2] * m[5] - m[4] * m[3]) / d;
  var yt = (-p[0] * m[1] + p[1] * m[0] + m[4] * m[1] - m[5] * m[0]) / d;
  return [xt, yt];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.applyTransform"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>applyTransform (p, m)](#apidoc.element.pdfjs-dist.PDFJS.Util.applyTransform)
- description and source-code
```javascript
function Util_applyTransform(p, m) {
  var xt = p[0] * m[0] + p[1] * m[2] + m[4];
  var yt = p[0] * m[1] + p[1] * m[3] + m[5];
  return [xt, yt];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.extendObj"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>extendObj (obj1, obj2)](#apidoc.element.pdfjs-dist.PDFJS.Util.extendObj)
- description and source-code
```javascript
function extendObj(obj1, obj2) {
  for (var key in obj2) {
    obj1[key] = obj2[key];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.getAxialAlignedBoundingBox"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>getAxialAlignedBoundingBox (r, m)](#apidoc.element.pdfjs-dist.PDFJS.Util.getAxialAlignedBoundingBox)
- description and source-code
```javascript
function Util_getAxialAlignedBoundingBox(r, m) {
  var p1 = Util.applyTransform(r, m);
  var p2 = Util.applyTransform(r.slice(2, 4), m);
  var p3 = Util.applyTransform([r[0], r[3]], m);
  var p4 = Util.applyTransform([r[2], r[1]], m);
  return [Math.min(p1[0], p2[0], p3[0], p4[0]), Math.min(p1[1], p2[1], p3[1], p4[1]), Math.max(p1[0], p2[0], p3[0], p4[0]), Math
.max(p1[1], p2[1], p3[1], p4[1])];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.getInheritableProperty"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>getInheritableProperty (dict, name, getArray)](#apidoc.element.pdfjs-dist.PDFJS.Util.getInheritableProperty)
- description and source-code
```javascript
function Util_getInheritableProperty(dict, name, getArray) {
  while (dict && !dict.has(name)) {
    dict = dict.get('Parent');
  }
  if (!dict) {
    return null;
  }
  return getArray ? dict.getArray(name) : dict.get(name);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.inherit"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>inherit (sub, base, prototype)](#apidoc.element.pdfjs-dist.PDFJS.Util.inherit)
- description and source-code
```javascript
function Util_inherit(sub, base, prototype) {
  sub.prototype = Object.create(base.prototype);
  sub.prototype.constructor = sub;
  for (var prop in prototype) {
    sub.prototype[prop] = prototype[prop];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.intersect"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>intersect (rect1, rect2)](#apidoc.element.pdfjs-dist.PDFJS.Util.intersect)
- description and source-code
```javascript
function Util_intersect(rect1, rect2) {
  function compare(a, b) {
    return a - b;
  }
  var orderedX = [rect1[0], rect1[2], rect2[0], rect2[2]].sort(compare),
      orderedY = [rect1[1], rect1[3], rect2[1], rect2[3]].sort(compare),
      result = [];
  rect1 = Util.normalizeRect(rect1);
  rect2 = Util.normalizeRect(rect2);
  if (orderedX[0] === rect1[0] && orderedX[1] === rect2[0] || orderedX[0] === rect2[0] && orderedX[1] === rect1[0]) {
    result[0] = orderedX[1];
    result[2] = orderedX[2];
  } else {
    return false;
  }
  if (orderedY[0] === rect1[1] && orderedY[1] === rect2[1] || orderedY[0] === rect2[1] && orderedY[1] === rect1[1]) {
    result[1] = orderedY[1];
    result[3] = orderedY[2];
  } else {
    return false;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.inverseTransform"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>inverseTransform (m)](#apidoc.element.pdfjs-dist.PDFJS.Util.inverseTransform)
- description and source-code
```javascript
function Util_inverseTransform(m) {
  var d = m[0] * m[3] - m[1] * m[2];
  return [m[3] / d, -m[1] / d, -m[2] / d, m[0] / d, (m[2] * m[5] - m[4] * m[3]) / d, (m[4] * m[1] - m[5] * m[0]) / d];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.loadScript"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>loadScript (src, callback)](#apidoc.element.pdfjs-dist.PDFJS.Util.loadScript)
- description and source-code
```javascript
function Util_loadScript(src, callback) {
  var script = document.createElement('script');
  var loaded = false;
  script.setAttribute('src', src);
  if (callback) {
    script.onload = function () {
      if (!loaded) {
        callback();
      }
      loaded = true;
    };
  }
  document.getElementsByTagName('head')[0].appendChild(script);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.makeCssRgb"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>makeCssRgb (r, g, b)](#apidoc.element.pdfjs-dist.PDFJS.Util.makeCssRgb)
- description and source-code
```javascript
function Util_makeCssRgb(r, g, b) {
  rgbBuf[1] = r;
  rgbBuf[3] = g;
  rgbBuf[5] = b;
  return rgbBuf.join('');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.normalizeRect"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>normalizeRect (rect)](#apidoc.element.pdfjs-dist.PDFJS.Util.normalizeRect)
- description and source-code
```javascript
function Util_normalizeRect(rect) {
  var r = rect.slice(0);
  if (rect[0] > rect[2]) {
    r[0] = rect[2];
    r[2] = rect[0];
  }
  if (rect[1] > rect[3]) {
    r[1] = rect[3];
    r[3] = rect[1];
  }
  return r;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.prependToArray"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>prependToArray (arr1, arr2)](#apidoc.element.pdfjs-dist.PDFJS.Util.prependToArray)
- description and source-code
```javascript
function Util_prependToArray(arr1, arr2) {
  Array.prototype.unshift.apply(arr1, arr2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.sign"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>sign (num)](#apidoc.element.pdfjs-dist.PDFJS.Util.sign)
- description and source-code
```javascript
function Util_sign(num) {
  return num < 0 ? -1 : 1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.singularValueDecompose2dScale"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>singularValueDecompose2dScale (m)](#apidoc.element.pdfjs-dist.PDFJS.Util.singularValueDecompose2dScale)
- description and source-code
```javascript
function Util_singularValueDecompose2dScale(m) {
  var transpose = [m[0], m[2], m[1], m[3]];
  var a = m[0] * transpose[0] + m[1] * transpose[2];
  var b = m[0] * transpose[1] + m[1] * transpose[3];
  var c = m[2] * transpose[0] + m[3] * transpose[2];
  var d = m[2] * transpose[1] + m[3] * transpose[3];
  var first = (a + d) / 2;
  var second = Math.sqrt((a + d) * (a + d) - 4 * (a * d - c * b)) / 2;
  var sx = first + second || 1;
  var sy = first - second || 1;
  return [Math.sqrt(sx), Math.sqrt(sy)];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.toRoman"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>toRoman (number, lowerCase)](#apidoc.element.pdfjs-dist.PDFJS.Util.toRoman)
- description and source-code
```javascript
function Util_toRoman(number, lowerCase) {
  assert(isInt(number) && number > 0, 'The number should be a positive integer.');
  var pos,
      romanBuf = [];
  while (number >= 1000) {
    number -= 1000;
    romanBuf.push('M');
  }
  pos = number / 100 | 0;
  number %= 100;
  romanBuf.push(ROMAN_NUMBER_MAP[pos]);
  pos = number / 10 | 0;
  number %= 10;
  romanBuf.push(ROMAN_NUMBER_MAP[10 + pos]);
  romanBuf.push(ROMAN_NUMBER_MAP[20 + number]);
  var romanStr = romanBuf.join('');
  return lowerCase ? romanStr.toLowerCase() : romanStr;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFJS.Util.transform"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFJS.Util.</span>transform (m1, m2)](#apidoc.element.pdfjs-dist.PDFJS.Util.transform)
- description and source-code
```javascript
function Util_transform(m1, m2) {
  return [m1[0] * m2[0] + m1[2] * m2[1], m1[1] * m2[0] + m1[3] * m2[1], m1[0] * m2[2] + m1[2] * m2[3], m1[1] * m2[2] + m1[3] * m2
[3], m1[0] * m2[4] + m1[2] * m2[5] + m1[4], m1[1] * m2[4] + m1[3] * m2[5] + m1[5]];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFWorker"></a>[module pdfjs-dist.PDFWorker](#apidoc.module.pdfjs-dist.PDFWorker)

#### <a name="apidoc.element.pdfjs-dist.PDFWorker.PDFWorker"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>PDFWorker (name, port)](#apidoc.element.pdfjs-dist.PDFWorker.PDFWorker)
- description and source-code
```javascript
function PDFWorker(name, port) {
  this.name = name;
  this.destroyed = false;
  this._readyCapability = createPromiseCapability();
  this._port = null;
  this._webWorker = null;
  this._messageHandler = null;
  if (port) {
    this._initializeFromPort(port);
    return;
  }
  this._initialize();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.PDFWorker.prototype"></a>[module pdfjs-dist.PDFWorker.prototype](#apidoc.module.pdfjs-dist.PDFWorker.prototype)

#### <a name="apidoc.element.pdfjs-dist.PDFWorker.prototype._initialize"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFWorker.prototype.</span>_initialize ()](#apidoc.element.pdfjs-dist.PDFWorker.prototype._initialize)
- description and source-code
```javascript
function PDFWorker_initialize() {
  if (!isWorkerDisabled && !getDefaultSetting('disableWorker') && typeof Worker !== 'undefined') {
    var workerSrc = getWorkerSrc();
    try {
      if (!isSameOrigin(window.location.href, workerSrc)) {
        workerSrc = createCDNWrapper(new URL(workerSrc, window.location).href);
      }
      var worker = new Worker(workerSrc);
      var messageHandler = new MessageHandler('main', 'worker', worker);
      var terminateEarly = function () {
        worker.removeEventListener('error', onWorkerError);
        messageHandler.destroy();
        worker.terminate();
        if (this.destroyed) {
          this._readyCapability.reject(new Error('Worker was destroyed'));
        } else {
          this._setupFakeWorker();
        }
      }.bind(this);
      var onWorkerError = function (event) {
        if (!this._webWorker) {
          terminateEarly();
        }
      }.bind(this);
      worker.addEventListener('error', onWorkerError);
      messageHandler.on('test', function PDFWorker_test(data) {
        worker.removeEventListener('error', onWorkerError);
        if (this.destroyed) {
          terminateEarly();
          return;
        }
        var supportTypedArray = data && data.supportTypedArray;
        if (supportTypedArray) {
          this._messageHandler = messageHandler;
          this._port = worker;
          this._webWorker = worker;
          if (!data.supportTransfers) {
            isPostMessageTransfersDisabled = true;
          }
          this._readyCapability.resolve();
          messageHandler.send('configure', { verbosity: getVerbosityLevel() });
        } else {
          this._setupFakeWorker();
          messageHandler.destroy();
          worker.terminate();
        }
      }.bind(this));
      messageHandler.on('console_log', function (data) {
        console.log.apply(console, data);
      });
      messageHandler.on('console_error', function (data) {
        console.error.apply(console, data);
      });
      messageHandler.on('ready', function (data) {
        worker.removeEventListener('error', onWorkerError);
        if (this.destroyed) {
          terminateEarly();
          return;
        }
        try {
          sendTest();
        } catch (e) {
          this._setupFakeWorker();
        }
      }.bind(this));
      var sendTest = function () {
        var postMessageTransfers = getDefaultSetting('postMessageTransfers') && !isPostMessageTransfersDisabled;
        var testObj = new Uint8Array([postMessageTransfers ? 255 : 0]);
        try {
          messageHandler.send('test', testObj, [testObj.buffer]);
        } catch (ex) {
          info('Cannot use postMessage transfers');
          testObj[0] = 0;
          messageHandler.send('test', testObj);
        }
      };
      sendTest();
      return;
    } catch (e) {
      info('The worker has been disabled.');
    }
  }
  this._setupFakeWorker();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFWorker.prototype._initializeFromPort"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFWorker.prototype.</span>_initializeFromPort (port)](#apidoc.element.pdfjs-dist.PDFWorker.prototype._initializeFromPort)
- description and source-code
```javascript
function PDFWorker_initializeFromPort(port) {
  this._port = port;
  this._messageHandler = new MessageHandler('main', 'worker', port);
  this._messageHandler.on('ready', function () {});
  this._readyCapability.resolve();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFWorker.prototype._setupFakeWorker"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFWorker.prototype.</span>_setupFakeWorker ()](#apidoc.element.pdfjs-dist.PDFWorker.prototype._setupFakeWorker)
- description and source-code
```javascript
function PDFWorker_setupFakeWorker() {
  if (!isWorkerDisabled && !getDefaultSetting('disableWorker')) {
    warn('Setting up fake worker.');
    isWorkerDisabled = true;
  }
  setupFakeWorkerGlobal().then(function (WorkerMessageHandler) {
    if (this.destroyed) {
      this._readyCapability.reject(new Error('Worker was destroyed'));
      return;
    }
    var isTypedArraysPresent = Uint8Array !== Float32Array;
    var port = new FakeWorkerPort(isTypedArraysPresent);
    this._port = port;
    var id = 'fake' + nextFakeWorkerId++;
    var workerHandler = new MessageHandler(id + '_worker', id, port);
    WorkerMessageHandler.setup(workerHandler, port);
    var messageHandler = new MessageHandler(id, id + '_worker', port);
    this._messageHandler = messageHandler;
    this._readyCapability.resolve();
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.PDFWorker.prototype.destroy"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.PDFWorker.prototype.</span>destroy ()](#apidoc.element.pdfjs-dist.PDFWorker.prototype.destroy)
- description and source-code
```javascript
function PDFWorker_destroy() {
  this.destroyed = true;
  if (this._webWorker) {
    this._webWorker.terminate();
    this._webWorker = null;
  }
  this._port = null;
  if (this._messageHandler) {
    this._messageHandler.destroy();
    this._messageHandler = null;
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.RenderingCancelledException"></a>[module pdfjs-dist.RenderingCancelledException](#apidoc.module.pdfjs-dist.RenderingCancelledException)

#### <a name="apidoc.element.pdfjs-dist.RenderingCancelledException.RenderingCancelledException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>RenderingCancelledException (msg, type)](#apidoc.element.pdfjs-dist.RenderingCancelledException.RenderingCancelledException)
- description and source-code
```javascript
function RenderingCancelledException(msg, type) {
  this.message = msg;
  this.type = type;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.RenderingCancelledException.constructor"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.RenderingCancelledException.</span>constructor (msg, type)](#apidoc.element.pdfjs-dist.RenderingCancelledException.constructor)
- description and source-code
```javascript
function RenderingCancelledException(msg, type) {
  this.message = msg;
  this.type = type;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.SVGGraphics"></a>[module pdfjs-dist.SVGGraphics](#apidoc.module.pdfjs-dist.SVGGraphics)

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.SVGGraphics"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>SVGGraphics (commonObjs, objs, forceDataSchema)](#apidoc.element.pdfjs-dist.SVGGraphics.SVGGraphics)
- description and source-code
```javascript
function SVGGraphics(commonObjs, objs, forceDataSchema) {
  this.current = new SVGExtraState();
  this.transformMatrix = IDENTITY_MATRIX;
  this.transformStack = [];
  this.extraStack = [];
  this.commonObjs = commonObjs;
  this.objs = objs;
  this.pendingEOFill = false;
  this.embedFonts = false;
  this.embeddedFonts = Object.create(null);
  this.cssStyle = null;
  this.forceDataSchema = !!forceDataSchema;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.SVGGraphics.prototype"></a>[module pdfjs-dist.SVGGraphics.prototype](#apidoc.module.pdfjs-dist.SVGGraphics.prototype)

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype._ensureClipGroup"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>_ensureClipGroup ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype._ensureClipGroup)
- description and source-code
```javascript
function SVGGraphics_ensureClipGroup() {
  if (!this.current.clipGroup) {
    var clipGroup = document.createElementNS(NS, 'svg:g');
    clipGroup.setAttributeNS(null, 'clip-path', this.current.activeClipUrl);
    this.svg.appendChild(clipGroup);
    this.current.clipGroup = clipGroup;
  }
  return this.current.clipGroup;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype._ensureTransformGroup"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>_ensureTransformGroup ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype._ensureTransformGroup)
- description and source-code
```javascript
function SVGGraphics_ensureTransformGroup() {
  if (!this.tgrp) {
    this.tgrp = document.createElementNS(NS, 'svg:g');
    this.tgrp.setAttributeNS(null, 'transform', pm(this.transformMatrix));
    if (this.current.activeClipUrl) {
      this._ensureClipGroup().appendChild(this.tgrp);
    } else {
      this.svg.appendChild(this.tgrp);
    }
  }
  return this.tgrp;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype._initialize"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>_initialize (viewport)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype._initialize)
- description and source-code
```javascript
function SVGGraphics_initialize(viewport) {
  var svg = document.createElementNS(NS, 'svg:svg');
  svg.setAttributeNS(null, 'version', '1.1');
  svg.setAttributeNS(null, 'width', viewport.width + 'px');
  svg.setAttributeNS(null, 'height', viewport.height + 'px');
  svg.setAttributeNS(null, 'preserveAspectRatio', 'none');
  svg.setAttributeNS(null, 'viewBox', '0 0 ' + viewport.width + ' ' + viewport.height);
  var definitions = document.createElementNS(NS, 'svg:defs');
  svg.appendChild(definitions);
  this.defs = definitions;
  var rootGroup = document.createElementNS(NS, 'svg:g');
  rootGroup.setAttributeNS(null, 'transform', pm(viewport.transform));
  svg.appendChild(rootGroup);
  this.svg = rootGroup;
  return svg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.addFontStyle"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>addFontStyle (fontObj)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.addFontStyle)
- description and source-code
```javascript
function SVGGraphics_addFontStyle(fontObj) {
  if (!this.cssStyle) {
    this.cssStyle = document.createElementNS(NS, 'svg:style');
    this.cssStyle.setAttributeNS(null, 'type', 'text/css');
    this.defs.appendChild(this.cssStyle);
  }
  var url = createObjectURL(fontObj.data, fontObj.mimetype, this.forceDataSchema);
  this.cssStyle.textContent += '@font-face { font-family: "' + fontObj.loadedName + '";' + ' src: url(' + url + '); }\n';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.beginText"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>beginText ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.beginText)
- description and source-code
```javascript
function SVGGraphics_beginText() {
  this.current.x = this.current.lineX = 0;
  this.current.y = this.current.lineY = 0;
  this.current.textMatrix = IDENTITY_MATRIX;
  this.current.lineMatrix = IDENTITY_MATRIX;
  this.current.tspan = document.createElementNS(NS, 'svg:tspan');
  this.current.txtElement = document.createElementNS(NS, 'svg:text');
  this.current.txtgrp = document.createElementNS(NS, 'svg:g');
  this.current.xcoords = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.clip"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>clip (type)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.clip)
- description and source-code
```javascript
function SVGGraphics_clip(type) {
  var current = this.current;
  var clipId = 'clippath' + clipCount;
  clipCount++;
  var clipPath = document.createElementNS(NS, 'svg:clipPath');
  clipPath.setAttributeNS(null, 'id', clipId);
  clipPath.setAttributeNS(null, 'transform', pm(this.transformMatrix));
  var clipElement = current.element.cloneNode();
  if (type === 'evenodd') {
    clipElement.setAttributeNS(null, 'clip-rule', 'evenodd');
  } else {
    clipElement.setAttributeNS(null, 'clip-rule', 'nonzero');
  }
  clipPath.appendChild(clipElement);
  this.defs.appendChild(clipPath);
  if (current.activeClipUrl) {
    current.clipGroup = null;
    this.extraStack.forEach(function (prev) {
      prev.clipGroup = null;
    });
  }
  current.activeClipUrl = 'url(#' + clipId + ')';
  this.tgrp = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.closeFillStroke"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>closeFillStroke ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.closeFillStroke)
- description and source-code
```javascript
function SVGGraphics_closeFillStroke() {
  this.closePath();
  this.fillStroke();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.closePath"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>closePath ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.closePath)
- description and source-code
```javascript
function SVGGraphics_closePath() {
  var current = this.current;
  var d = current.path.getAttributeNS(null, 'd');
  d += 'Z';
  current.path.setAttributeNS(null, 'd', d);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.closeStroke"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>closeStroke ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.closeStroke)
- description and source-code
```javascript
function SVGGraphics_closeStroke() {
  this.closePath();
  this.stroke();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.constructPath"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>constructPath (ops, args)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.constructPath)
- description and source-code
```javascript
function SVGGraphics_constructPath(ops, args) {
  var current = this.current;
  var x = current.x,
      y = current.y;
  current.path = document.createElementNS(NS, 'svg:path');
  var d = [];
  var opLength = ops.length;
  for (var i = 0, j = 0; i < opLength; i++) {
    switch (ops[i] | 0) {
      case OPS.rectangle:
        x = args[j++];
        y = args[j++];
        var width = args[j++];
        var height = args[j++];
        var xw = x + width;
        var yh = y + height;
        d.push('M', pf(x), pf(y), 'L', pf(xw), pf(y), 'L', pf(xw), pf(yh), 'L', pf(x), pf(yh), 'Z');
        break;
      case OPS.moveTo:
        x = args[j++];
        y = args[j++];
        d.push('M', pf(x), pf(y));
        break;
      case OPS.lineTo:
        x = args[j++];
        y = args[j++];
        d.push('L', pf(x), pf(y));
        break;
      case OPS.curveTo:
        x = args[j + 4];
        y = args[j + 5];
        d.push('C', pf(args[j]), pf(args[j + 1]), pf(args[j + 2]), pf(args[j + 3]), pf(x), pf(y));
        j += 6;
        break;
      case OPS.curveTo2:
        x = args[j + 2];
        y = args[j + 3];
        d.push('C', pf(x), pf(y), pf(args[j]), pf(args[j + 1]), pf(args[j + 2]), pf(args[j + 3]));
        j += 4;
        break;
      case OPS.curveTo3:
        x = args[j + 2];
        y = args[j + 3];
        d.push('C', pf(args[j]), pf(args[j + 1]), pf(x), pf(y), pf(x), pf(y));
        j += 4;
        break;
      case OPS.closePath:
        d.push('Z');
        break;
    }
  }
  current.path.setAttributeNS(null, 'd', d.join(' '));
  current.path.setAttributeNS(null, 'stroke-miterlimit', pf(current.miterLimit));
  current.path.setAttributeNS(null, 'stroke-linecap', current.lineCap);
  current.path.setAttributeNS(null, 'stroke-linejoin', current.lineJoin);
  current.path.setAttributeNS(null, 'stroke-width', pf(current.lineWidth) + 'px');
  current.path.setAttributeNS(null, 'stroke-dasharray', current.dashArray.map(pf).join(' '));
  current.path.setAttributeNS(null, 'stroke-dashoffset', pf(current.dashPhase) + 'px');
  current.path.setAttributeNS(null, 'fill', 'none');
  this._ensureTransformGroup().appendChild(current.path);
  current.element = current.path;
  current.setCurrentPoint(x, y);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.convertOpList"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>convertOpList (operatorList)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.convertOpList)
- description and source-code
```javascript
function SVGGraphics_convertOpList(operatorList) {
  var argsArray = operatorList.argsArray;
  var fnArray = operatorList.fnArray;
  var fnArrayLen = fnArray.length;
  var REVOPS = [];
  var opList = [];
  for (var op in OPS) {
    REVOPS[OPS[op]] = op;
  }
  for (var x = 0; x < fnArrayLen; x++) {
    var fnId = fnArray[x];
    opList.push({
      'fnId': fnId,
      'fn': REVOPS[fnId],
      'args': argsArray[x]
    });
  }
  return opListToTree(opList);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.endPath"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>endPath ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.endPath)
- description and source-code
```javascript
function SVGGraphics_endPath() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.endText"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>endText ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.endText)
- description and source-code
```javascript
function SVGGraphics_endText() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.eoFill"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>eoFill ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.eoFill)
- description and source-code
```javascript
function SVGGraphics_eoFill() {
  var current = this.current;
  current.element.setAttributeNS(null, 'fill', current.fillColor);
  current.element.setAttributeNS(null, 'fill-rule', 'evenodd');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.eoFillStroke"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>eoFillStroke ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.eoFillStroke)
- description and source-code
```javascript
function SVGGraphics_eoFillStroke() {
  this.current.element.setAttributeNS(null, 'fill-rule', 'evenodd');
  this.fillStroke();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.executeOpTree"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>executeOpTree (opTree)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.executeOpTree)
- description and source-code
```javascript
function SVGGraphics_executeOpTree(opTree) {
  var opTreeLen = opTree.length;
  for (var x = 0; x < opTreeLen; x++) {
    var fn = opTree[x].fn;
    var fnId = opTree[x].fnId;
    var args = opTree[x].args;
    switch (fnId | 0) {
      case OPS.beginText:
        this.beginText();
        break;
      case OPS.setLeading:
        this.setLeading(args);
        break;
      case OPS.setLeadingMoveText:
        this.setLeadingMoveText(args[0], args[1]);
        break;
      case OPS.setFont:
        this.setFont(args);
        break;
      case OPS.showText:
        this.showText(args[0]);
        break;
      case OPS.showSpacedText:
        this.showText(args[0]);
        break;
      case OPS.endText:
        this.endText();
        break;
      case OPS.moveText:
        this.moveText(args[0], args[1]);
        break;
      case OPS.setCharSpacing:
        this.setCharSpacing(args[0]);
        break;
      case OPS.setWordSpacing:
        this.setWordSpacing(args[0]);
        break;
      case OPS.setHScale:
        this.setHScale(args[0]);
        break;
      case OPS.setTextMatrix:
        this.setTextMatrix(args[0], args[1], args[2], args[3], args[4], args[5]);
        break;
      case OPS.setLineWidth:
        this.setLineWidth(args[0]);
        break;
      case OPS.setLineJoin:
        this.setLineJoin(args[0]);
        break;
      case OPS.setLineCap:
        this.setLineCap(args[0]);
        break;
      case OPS.setMiterLimit:
        this.setMiterLimit(args[0]);
        break;
      case OPS.setFillRGBColor:
        this.setFillRGBColor(args[0], args[1], args[2]);
        break;
      case OPS.setStrokeRGBColor:
        this.setStrokeRGBColor(args[0], args[1], args[2]);
        break;
      case OPS.setDash:
        this.setDash(args[0], args[1]);
        break;
      case OPS.setGState:
        this.setGState(args[0]);
        break;
      case OPS.fill:
        this.fill();
        break;
      case OPS.eoFill:
        this.eoFill();
        break;
      case OPS.stroke:
        this.stroke();
        break;
      case OPS.fillStroke:
        this.fillStroke();
        break;
      case OPS.eoFillStroke:
        this.eoFillStroke();
        break;
      case OPS.clip:
        this.clip('nonzero');
        break;
      case OPS.eoClip:
        this.clip('evenodd');
        break;
      case OPS.paintSolidColorImageMask:
        this.paintSolidColorImageMask();
        break;
      case OPS.paintJpegXObject:
        this.paintJpegXObject(args[0], args[1], args[2]);
        break;
      case OPS.paintImageXObject:
        this.paintImageXObject(args[0]);
        break;
      case OPS.paintInlineImageXObject:
        this.paintInlineImageXObject(args[0]);
        break;
      case OPS.paintImageMaskXObject:
        this.paintImageMaskXObject(args[0]);
        break;
      case OPS.paintFormXObjectBegin:
        this.paintFormXObjectBegin(args[0], args[1]);
        break;
      case OPS.paintFormXObjectEnd:
        this.paintFormXObjectEnd();
        break;
      case OPS.closePath:
        this.closePath();
        break;
      case OPS.closeStroke:
        this.closeStroke();
        break;
      case OPS.closeFillStroke:
        this.closeFillStroke();
        break;
      case OPS.nextLine:
        this.nextLine();
        break;
      case OPS.transform:
        this.transform(args[0], args[1], args[2], args[3], args[4], args[5]);
        break;
      case OPS.constructPath:
        this.constructPath(args[0], args[1]);
        break;
      case OPS.endPath:
        this.endPath();
        break;
      case 92:
        this.group(opTree[x].items);
        break;
      default:
        warn('Unimplemented operator ' + fn);
        break;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.fill"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>fill ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.fill)
- description and source-code
```javascript
function SVGGraphics_fill() {
  var current = this.current;
  current.element.setAttributeNS(null, 'fill', current.fillColor);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.fillStroke"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>fillStroke ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.fillStroke)
- description and source-code
```javascript
function SVGGraphics_fillStroke() {
  this.stroke();
  this.fill();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.getSVG"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>getSVG (operatorList, viewport)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.getSVG)
- description and source-code
```javascript
function SVGGraphics_getSVG(operatorList, viewport) {
  this.viewport = viewport;
  var svgElement = this._initialize(viewport);
  return this.loadDependencies(operatorList).then(function () {
    this.transformMatrix = IDENTITY_MATRIX;
    var opTree = this.convertOpList(operatorList);
    this.executeOpTree(opTree);
    return svgElement;
  }.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.group"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>group (items)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.group)
- description and source-code
```javascript
function SVGGraphics_group(items) {
  this.save();
  this.executeOpTree(items);
  this.restore();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.loadDependencies"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>loadDependencies (operatorList)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.loadDependencies)
- description and source-code
```javascript
function SVGGraphics_loadDependencies(operatorList) {
  var fnArray = operatorList.fnArray;
  var fnArrayLen = fnArray.length;
  var argsArray = operatorList.argsArray;
  var self = this;
  for (var i = 0; i < fnArrayLen; i++) {
    if (OPS.dependency === fnArray[i]) {
      var deps = argsArray[i];
      for (var n = 0, nn = deps.length; n < nn; n++) {
        var obj = deps[n];
        var common = obj.substring(0, 2) === 'g_';
        var promise;
        if (common) {
          promise = new Promise(function (resolve) {
            self.commonObjs.get(obj, resolve);
          });
        } else {
          promise = new Promise(function (resolve) {
            self.objs.get(obj, resolve);
          });
        }
        this.current.dependencies.push(promise);
      }
    }
  }
  return Promise.all(this.current.dependencies);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.moveText"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>moveText (x, y)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.moveText)
- description and source-code
```javascript
function SVGGraphics_moveText(x, y) {
  var current = this.current;
  this.current.x = this.current.lineX += x;
  this.current.y = this.current.lineY += y;
  current.xcoords = [];
  current.tspan = document.createElementNS(NS, 'svg:tspan');
  current.tspan.setAttributeNS(null, 'font-family', current.fontFamily);
  current.tspan.setAttributeNS(null, 'font-size', pf(current.fontSize) + 'px');
  current.tspan.setAttributeNS(null, 'y', pf(-current.y));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.nextLine"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>nextLine ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.nextLine)
- description and source-code
```javascript
function SVGGraphics_nextLine() {
  this.moveText(0, this.current.leading);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintFormXObjectBegin"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>paintFormXObjectBegin (matrix, bbox)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintFormXObjectBegin)
- description and source-code
```javascript
function SVGGraphics_paintFormXObjectBegin(matrix, bbox) {
  if (isArray(matrix) && matrix.length === 6) {
    this.transform(matrix[0], matrix[1], matrix[2], matrix[3], matrix[4], matrix[5]);
  }
  if (isArray(bbox) && bbox.length === 4) {
    var width = bbox[2] - bbox[0];
    var height = bbox[3] - bbox[1];
    var cliprect = document.createElementNS(NS, 'svg:rect');
    cliprect.setAttributeNS(null, 'x', bbox[0]);
    cliprect.setAttributeNS(null, 'y', bbox[1]);
    cliprect.setAttributeNS(null, 'width', pf(width));
    cliprect.setAttributeNS(null, 'height', pf(height));
    this.current.element = cliprect;
    this.clip('nonzero');
    this.endPath();
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintFormXObjectEnd"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>paintFormXObjectEnd ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintFormXObjectEnd)
- description and source-code
```javascript
function SVGGraphics_paintFormXObjectEnd() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintImageMaskXObject"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>paintImageMaskXObject (imgData)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintImageMaskXObject)
- description and source-code
```javascript
function SVGGraphics_paintImageMaskXObject(imgData) {
  var current = this.current;
  var width = imgData.width;
  var height = imgData.height;
  var fillColor = current.fillColor;
  current.maskId = 'mask' + maskCount++;
  var mask = document.createElementNS(NS, 'svg:mask');
  mask.setAttributeNS(null, 'id', current.maskId);
  var rect = document.createElementNS(NS, 'svg:rect');
  rect.setAttributeNS(null, 'x', '0');
  rect.setAttributeNS(null, 'y', '0');
  rect.setAttributeNS(null, 'width', pf(width));
  rect.setAttributeNS(null, 'height', pf(height));
  rect.setAttributeNS(null, 'fill', fillColor);
  rect.setAttributeNS(null, 'mask', 'url(#' + current.maskId + ')');
  this.defs.appendChild(mask);
  this._ensureTransformGroup().appendChild(rect);
  this.paintInlineImageXObject(imgData, mask);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintImageXObject"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>paintImageXObject (objId)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintImageXObject)
- description and source-code
```javascript
function SVGGraphics_paintImageXObject(objId) {
  var imgData = this.objs.get(objId);
  if (!imgData) {
    warn('Dependent image isn\'t ready yet');
    return;
  }
  this.paintInlineImageXObject(imgData);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintInlineImageXObject"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>paintInlineImageXObject (imgData, mask)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintInlineImageXObject)
- description and source-code
```javascript
function SVGGraphics_paintInlineImageXObject(imgData, mask) {
  var width = imgData.width;
  var height = imgData.height;
  var imgSrc = convertImgDataToPng(imgData, this.forceDataSchema);
  var cliprect = document.createElementNS(NS, 'svg:rect');
  cliprect.setAttributeNS(null, 'x', '0');
  cliprect.setAttributeNS(null, 'y', '0');
  cliprect.setAttributeNS(null, 'width', pf(width));
  cliprect.setAttributeNS(null, 'height', pf(height));
  this.current.element = cliprect;
  this.clip('nonzero');
  var imgEl = document.createElementNS(NS, 'svg:image');
  imgEl.setAttributeNS(XLINK_NS, 'xlink:href', imgSrc);
  imgEl.setAttributeNS(null, 'x', '0');
  imgEl.setAttributeNS(null, 'y', pf(-height));
  imgEl.setAttributeNS(null, 'width', pf(width) + 'px');
  imgEl.setAttributeNS(null, 'height', pf(height) + 'px');
  imgEl.setAttributeNS(null, 'transform', 'scale(' + pf(1 / width) + ' ' + pf(-1 / height) + ')');
  if (mask) {
    mask.appendChild(imgEl);
  } else {
    this._ensureTransformGroup().appendChild(imgEl);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintJpegXObject"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>paintJpegXObject (objId, w, h)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintJpegXObject)
- description and source-code
```javascript
function SVGGraphics_paintJpegXObject(objId, w, h) {
  var imgObj = this.objs.get(objId);
  var imgEl = document.createElementNS(NS, 'svg:image');
  imgEl.setAttributeNS(XLINK_NS, 'xlink:href', imgObj.src);
  imgEl.setAttributeNS(null, 'width', imgObj.width + 'px');
  imgEl.setAttributeNS(null, 'height', imgObj.height + 'px');
  imgEl.setAttributeNS(null, 'x', '0');
  imgEl.setAttributeNS(null, 'y', pf(-h));
  imgEl.setAttributeNS(null, 'transform', 'scale(' + pf(1 / w) + ' ' + pf(-1 / h) + ')');
  this._ensureTransformGroup().appendChild(imgEl);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintSolidColorImageMask"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>paintSolidColorImageMask ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.paintSolidColorImageMask)
- description and source-code
```javascript
function SVGGraphics_paintSolidColorImageMask() {
  var current = this.current;
  var rect = document.createElementNS(NS, 'svg:rect');
  rect.setAttributeNS(null, 'x', '0');
  rect.setAttributeNS(null, 'y', '0');
  rect.setAttributeNS(null, 'width', '1px');
  rect.setAttributeNS(null, 'height', '1px');
  rect.setAttributeNS(null, 'fill', current.fillColor);
  this._ensureTransformGroup().appendChild(rect);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.restore"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>restore ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.restore)
- description and source-code
```javascript
function SVGGraphics_restore() {
  this.transformMatrix = this.transformStack.pop();
  this.current = this.extraStack.pop();
  this.tgrp = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.save"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>save ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.save)
- description and source-code
```javascript
function SVGGraphics_save() {
  this.transformStack.push(this.transformMatrix);
  var old = this.current;
  this.extraStack.push(old);
  this.current = old.clone();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setCharSpacing"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setCharSpacing (charSpacing)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setCharSpacing)
- description and source-code
```javascript
function SVGGraphics_setCharSpacing(charSpacing) {
  this.current.charSpacing = charSpacing;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setDash"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setDash (dashArray, dashPhase)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setDash)
- description and source-code
```javascript
function SVGGraphics_setDash(dashArray, dashPhase) {
  this.current.dashArray = dashArray;
  this.current.dashPhase = dashPhase;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setFillRGBColor"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setFillRGBColor (r, g, b)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setFillRGBColor)
- description and source-code
```javascript
function SVGGraphics_setFillRGBColor(r, g, b) {
  var color = Util.makeCssRgb(r, g, b);
  this.current.fillColor = color;
  this.current.tspan = document.createElementNS(NS, 'svg:tspan');
  this.current.xcoords = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setFont"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setFont (details)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setFont)
- description and source-code
```javascript
function SVGGraphics_setFont(details) {
  var current = this.current;
  var fontObj = this.commonObjs.get(details[0]);
  var size = details[1];
  this.current.font = fontObj;
  if (this.embedFonts && fontObj.data && !this.embeddedFonts[fontObj.loadedName]) {
    this.addFontStyle(fontObj);
    this.embeddedFonts[fontObj.loadedName] = fontObj;
  }
  current.fontMatrix = fontObj.fontMatrix ? fontObj.fontMatrix : FONT_IDENTITY_MATRIX;
  var bold = fontObj.black ? fontObj.bold ? 'bolder' : 'bold' : fontObj.bold ? 'bold' : 'normal';
  var italic = fontObj.italic ? 'italic' : 'normal';
  if (size < 0) {
    size = -size;
    current.fontDirection = -1;
  } else {
    current.fontDirection = 1;
  }
  current.fontSize = size;
  current.fontFamily = fontObj.loadedName;
  current.fontWeight = bold;
  current.fontStyle = italic;
  current.tspan = document.createElementNS(NS, 'svg:tspan');
  current.tspan.setAttributeNS(null, 'y', pf(-current.y));
  current.xcoords = [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setGState"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setGState (states)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setGState)
- description and source-code
```javascript
function SVGGraphics_setGState(states) {
  for (var i = 0, ii = states.length; i < ii; i++) {
    var state = states[i];
    var key = state[0];
    var value = state[1];
    switch (key) {
      case 'LW':
        this.setLineWidth(value);
        break;
      case 'LC':
        this.setLineCap(value);
        break;
      case 'LJ':
        this.setLineJoin(value);
        break;
      case 'ML':
        this.setMiterLimit(value);
        break;
      case 'D':
        this.setDash(value[0], value[1]);
        break;
      case 'Font':
        this.setFont(value);
        break;
      default:
        warn('Unimplemented graphic state ' + key);
        break;
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setHScale"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setHScale (scale)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setHScale)
- description and source-code
```javascript
function SVGGraphics_setHScale(scale) {
  this.current.textHScale = scale / 100;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setLeading"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setLeading (leading)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setLeading)
- description and source-code
```javascript
function SVGGraphics_setLeading(leading) {
  this.current.leading = -leading;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setLeadingMoveText"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setLeadingMoveText (x, y)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setLeadingMoveText)
- description and source-code
```javascript
function SVGGraphics_setLeadingMoveText(x, y) {
  this.setLeading(-y);
  this.moveText(x, y);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setLineCap"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setLineCap (style)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setLineCap)
- description and source-code
```javascript
function SVGGraphics_setLineCap(style) {
  this.current.lineCap = LINE_CAP_STYLES[style];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setLineJoin"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setLineJoin (style)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setLineJoin)
- description and source-code
```javascript
function SVGGraphics_setLineJoin(style) {
  this.current.lineJoin = LINE_JOIN_STYLES[style];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setLineWidth"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setLineWidth (width)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setLineWidth)
- description and source-code
```javascript
function SVGGraphics_setLineWidth(width) {
  this.current.lineWidth = width;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setMiterLimit"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setMiterLimit (limit)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setMiterLimit)
- description and source-code
```javascript
function SVGGraphics_setMiterLimit(limit) {
  this.current.miterLimit = limit;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setStrokeRGBColor"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setStrokeRGBColor (r, g, b)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setStrokeRGBColor)
- description and source-code
```javascript
function SVGGraphics_setStrokeRGBColor(r, g, b) {
  var color = Util.makeCssRgb(r, g, b);
  this.current.strokeColor = color;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setTextMatrix"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setTextMatrix (a, b, c, d, e, f)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setTextMatrix)
- description and source-code
```javascript
function SVGGraphics_setTextMatrix(a, b, c, d, e, f) {
  var current = this.current;
  this.current.textMatrix = this.current.lineMatrix = [a, b, c, d, e, f];
  this.current.x = this.current.lineX = 0;
  this.current.y = this.current.lineY = 0;
  current.xcoords = [];
  current.tspan = document.createElementNS(NS, 'svg:tspan');
  current.tspan.setAttributeNS(null, 'font-family', current.fontFamily);
  current.tspan.setAttributeNS(null, 'font-size', pf(current.fontSize) + 'px');
  current.tspan.setAttributeNS(null, 'y', pf(-current.y));
  current.txtElement = document.createElementNS(NS, 'svg:text');
  current.txtElement.appendChild(current.tspan);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setTextRise"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setTextRise (textRise)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setTextRise)
- description and source-code
```javascript
function SVGGraphics_setTextRise(textRise) {
  this.current.textRise = textRise;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.setWordSpacing"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>setWordSpacing (wordSpacing)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.setWordSpacing)
- description and source-code
```javascript
function SVGGraphics_setWordSpacing(wordSpacing) {
  this.current.wordSpacing = wordSpacing;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.showText"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>showText (glyphs)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.showText)
- description and source-code
```javascript
function SVGGraphics_showText(glyphs) {
  var current = this.current;
  var font = current.font;
  var fontSize = current.fontSize;
  if (fontSize === 0) {
    return;
  }
  var charSpacing = current.charSpacing;
  var wordSpacing = current.wordSpacing;
  var fontDirection = current.fontDirection;
  var textHScale = current.textHScale * fontDirection;
  var glyphsLength = glyphs.length;
  var vertical = font.vertical;
  var widthAdvanceScale = fontSize * current.fontMatrix[0];
  var x = 0,
      i;
  for (i = 0; i < glyphsLength; ++i) {
    var glyph = glyphs[i];
    if (glyph === null) {
      x += fontDirection * wordSpacing;
      continue;
    } else if (isNum(glyph)) {
      x += -glyph * fontSize * 0.001;
      continue;
    }
    current.xcoords.push(current.x + x * textHScale);
    var width = glyph.width;
    var character = glyph.fontChar;
    var charWidth = width * widthAdvanceScale + charSpacing * fontDirection;
    x += charWidth;
    current.tspan.textContent += character;
  }
  if (vertical) {
    current.y -= x * textHScale;
  } else {
    current.x += x * textHScale;
  }
  current.tspan.setAttributeNS(null, 'x', current.xcoords.map(pf).join(' '));
  current.tspan.setAttributeNS(null, 'y', pf(-current.y));
  current.tspan.setAttributeNS(null, 'font-family', current.fontFamily);
  current.tspan.setAttributeNS(null, 'font-size', pf(current.fontSize) + 'px');
  if (current.fontStyle !== SVG_DEFAULTS.fontStyle) {
    current.tspan.setAttributeNS(null, 'font-style', current.fontStyle);
  }
  if (current.fontWeight !== SVG_DEFAULTS.fontWeight) {
    current.tspan.setAttributeNS(null, 'font-weight', current.fontWeight);
  }
  if (current.fillColor !== SVG_DEFAULTS.fillColor) {
    current.tspan.setAttributeNS(null, 'fill', current.fillColor);
  }
  current.txtElement.setAttributeNS(null, 'transform', pm(current.textMatrix) + ' scale(1, -1)');
  current.txtElement.setAttributeNS(XML_NS, 'xml:space', 'preserve');
  current.txtElement.appendChild(current.tspan);
  current.txtgrp.appendChild(current.txtElement);
  this._ensureTransformGroup().appendChild(current.txtElement);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.stroke"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>stroke ()](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.stroke)
- description and source-code
```javascript
function SVGGraphics_stroke() {
  var current = this.current;
  current.element.setAttributeNS(null, 'stroke', current.strokeColor);
  current.element.setAttributeNS(null, 'fill', 'none');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.SVGGraphics.prototype.transform"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.SVGGraphics.prototype.</span>transform (a, b, c, d, e, f)](#apidoc.element.pdfjs-dist.SVGGraphics.prototype.transform)
- description and source-code
```javascript
function SVGGraphics_transform(a, b, c, d, e, f) {
  var transformMatrix = [a, b, c, d, e, f];
  this.transformMatrix = Util.transform(this.transformMatrix, transformMatrix);
  this.tgrp = null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.UnexpectedResponseException"></a>[module pdfjs-dist.UnexpectedResponseException](#apidoc.module.pdfjs-dist.UnexpectedResponseException)

#### <a name="apidoc.element.pdfjs-dist.UnexpectedResponseException.UnexpectedResponseException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.</span>UnexpectedResponseException (msg, status)](#apidoc.element.pdfjs-dist.UnexpectedResponseException.UnexpectedResponseException)
- description and source-code
```javascript
function UnexpectedResponseException(msg, status) {
  this.name = 'UnexpectedResponseException';
  this.message = msg;
  this.status = status;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.UnexpectedResponseException.constructor"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.UnexpectedResponseException.</span>constructor (msg, status)](#apidoc.element.pdfjs-dist.UnexpectedResponseException.constructor)
- description and source-code
```javascript
function UnexpectedResponseException(msg, status) {
  this.name = 'UnexpectedResponseException';
  this.message = msg;
  this.status = status;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.pdfjs-dist.pdf"></a>[module pdfjs-dist.pdf](#apidoc.module.pdfjs-dist.pdf)

#### <a name="apidoc.element.pdfjs-dist.pdf.CustomStyle"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>CustomStyle ()](#apidoc.element.pdfjs-dist.pdf.CustomStyle)
- description and source-code
```javascript
function CustomStyle() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.InvalidPDFException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>InvalidPDFException (msg)](#apidoc.element.pdfjs-dist.pdf.InvalidPDFException)
- description and source-code
```javascript
function InvalidPDFException(msg) {
  this.name = 'InvalidPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.MissingPDFException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>MissingPDFException (msg)](#apidoc.element.pdfjs-dist.pdf.MissingPDFException)
- description and source-code
```javascript
function MissingPDFException(msg) {
  this.name = 'MissingPDFException';
  this.message = msg;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.PDFDataRangeTransport"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>PDFDataRangeTransport (length, initialData)](#apidoc.element.pdfjs-dist.pdf.PDFDataRangeTransport)
- description and source-code
```javascript
function PDFDataRangeTransport(length, initialData) {
  this.length = length;
  this.initialData = initialData;
  this._rangeListeners = [];
  this._progressListeners = [];
  this._progressiveReadListeners = [];
  this._readyCapability = createPromiseCapability();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.PDFWorker"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>PDFWorker (name, port)](#apidoc.element.pdfjs-dist.pdf.PDFWorker)
- description and source-code
```javascript
function PDFWorker(name, port) {
  this.name = name;
  this.destroyed = false;
  this._readyCapability = createPromiseCapability();
  this._port = null;
  this._webWorker = null;
  this._messageHandler = null;
  if (port) {
    this._initializeFromPort(port);
    return;
  }
  this._initialize();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.RenderingCancelledException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>RenderingCancelledException (msg, type)](#apidoc.element.pdfjs-dist.pdf.RenderingCancelledException)
- description and source-code
```javascript
function RenderingCancelledException(msg, type) {
  this.message = msg;
  this.type = type;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.SVGGraphics"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>SVGGraphics (commonObjs, objs, forceDataSchema)](#apidoc.element.pdfjs-dist.pdf.SVGGraphics)
- description and source-code
```javascript
function SVGGraphics(commonObjs, objs, forceDataSchema) {
  this.current = new SVGExtraState();
  this.transformMatrix = IDENTITY_MATRIX;
  this.transformStack = [];
  this.extraStack = [];
  this.commonObjs = commonObjs;
  this.objs = objs;
  this.pendingEOFill = false;
  this.embedFonts = false;
  this.embeddedFonts = Object.create(null);
  this.cssStyle = null;
  this.forceDataSchema = !!forceDataSchema;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.UnexpectedResponseException"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>UnexpectedResponseException (msg, status)](#apidoc.element.pdfjs-dist.pdf.UnexpectedResponseException)
- description and source-code
```javascript
function UnexpectedResponseException(msg, status) {
  this.name = 'UnexpectedResponseException';
  this.message = msg;
  this.status = status;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.addLinkAttributes"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>addLinkAttributes (link, params)](#apidoc.element.pdfjs-dist.pdf.addLinkAttributes)
- description and source-code
```javascript
function addLinkAttributes(link, params) {
  var url = params && params.url;
  link.href = link.title = url ? removeNullCharacters(url) : '';
  if (url) {
    var target = params.target;
    if (typeof target === 'undefined') {
      target = getDefaultSetting('externalLinkTarget');
    }
    link.target = LinkTargetStringMap[target];
    var rel = params.rel;
    if (typeof rel === 'undefined') {
      rel = getDefaultSetting('externalLinkRel');
    }
    link.rel = rel;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.createBlob"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>createBlob (data, contentType)](#apidoc.element.pdfjs-dist.pdf.createBlob)
- description and source-code
```javascript
function createBlob(data, contentType) {
  if (typeof Blob !== 'undefined') {
    return new Blob([data], { type: contentType });
  }
  warn('The "Blob" constructor is not supported.');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.createObjectURL"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>createObjectURL (data, contentType, forceDataSchema)](#apidoc.element.pdfjs-dist.pdf.createObjectURL)
- description and source-code
```javascript
function createObjectURL(data, contentType, forceDataSchema) {
  if (!forceDataSchema && typeof URL !== 'undefined' && URL.createObjectURL) {
    var blob = createBlob(data, contentType);
    return URL.createObjectURL(blob);
  }
  var buffer = 'data:' + contentType + ';base64,';
  for (var i = 0, ii = data.length; i < ii; i += 3) {
    var b1 = data[i] & 0xFF;
    var b2 = data[i + 1] & 0xFF;
    var b3 = data[i + 2] & 0xFF;
    var d1 = b1 >> 2,
        d2 = (b1 & 3) << 4 | b2 >> 4;
    var d3 = i + 1 < ii ? (b2 & 0xF) << 2 | b3 >> 6 : 64;
    var d4 = i + 2 < ii ? b3 & 0x3F : 64;
    buffer += digits[d1] + digits[d2] + digits[d3] + digits[d4];
  }
  return buffer;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.createPromiseCapability"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>createPromiseCapability ()](#apidoc.element.pdfjs-dist.pdf.createPromiseCapability)
- description and source-code
```javascript
function createPromiseCapability() {
  var capability = {};
  capability.promise = new Promise(function (resolve, reject) {
    capability.resolve = resolve;
    capability.reject = reject;
  });
  return capability;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.createValidAbsoluteUrl"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>createValidAbsoluteUrl (url, baseUrl)](#apidoc.element.pdfjs-dist.pdf.createValidAbsoluteUrl)
- description and source-code
```javascript
function createValidAbsoluteUrl(url, baseUrl) {
  if (!url) {
    return null;
  }
  try {
    var absoluteUrl = baseUrl ? new URL(url, baseUrl) : new URL(url);
    if (isValidProtocol(absoluteUrl)) {
      return absoluteUrl;
    }
  } catch (ex) {}
  return null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.getDocument"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>getDocument (src, pdfDataRangeTransport, passwordCallback, progressCallback)](#apidoc.element.pdfjs-dist.pdf.getDocument)
- description and source-code
```javascript
function getDocument(src, pdfDataRangeTransport, passwordCallback, progressCallback) {
  var task = new PDFDocumentLoadingTask();
  if (arguments.length > 1) {
    deprecated('getDocument is called with pdfDataRangeTransport, ' + 'passwordCallback or progressCallback argument');
  }
  if (pdfDataRangeTransport) {
    if (!(pdfDataRangeTransport instanceof PDFDataRangeTransport)) {
      pdfDataRangeTransport = Object.create(pdfDataRangeTransport);
      pdfDataRangeTransport.length = src.length;
      pdfDataRangeTransport.initialData = src.initialData;
      if (!pdfDataRangeTransport.abort) {
        pdfDataRangeTransport.abort = function () {};
      }
    }
    src = Object.create(src);
    src.range = pdfDataRangeTransport;
  }
  task.onPassword = passwordCallback || null;
  task.onProgress = progressCallback || null;
  var source;
  if (typeof src === 'string') {
    source = { url: src };
  } else if (isArrayBuffer(src)) {
    source = { data: src };
  } else if (src instanceof PDFDataRangeTransport) {
    source = { range: src };
  } else {
    if (typeof src !== 'object') {
      error('Invalid parameter in getDocument, need either Uint8Array, ' + 'string or a parameter object');
    }
    if (!src.url && !src.data && !src.range) {
      error('Invalid parameter object: need either .data, .range or .url');
    }
    source = src;
  }
  var params = {};
  var rangeTransport = null;
  var worker = null;
  for (var key in source) {
    if (key === 'url' && typeof window !== 'undefined') {
      params[key] = new URL(source[key], window.location).href;
      continue;
    } else if (key === 'range') {
      rangeTransport = source[key];
      continue;
    } else if (key === 'worker') {
      worker = source[key];
      continue;
    } else if (key === 'data' && !(source[key] instanceof Uint8Array)) {
      var pdfBytes = source[key];
      if (typeof pdfBytes === 'string') {
        params[key] = stringToBytes(pdfBytes);
      } else if (typeof pdfBytes === 'object' && pdfBytes !== null && !isNaN(pdfBytes.length)) {
        params[key] = new Uint8Array(pdfBytes);
      } else if (isArrayBuffer(pdfBytes)) {
        params[key] = new Uint8Array(pdfBytes);
      } else {
        error('Invalid PDF binary data: either typed array, string or ' + 'array-like object is expected in the data property.');
      }
      continue;
    }
    params[key] = source[key];
  }
  params.rangeChunkSize = params.rangeChunkSize || DEFAULT_RANGE_CHUNK_SIZE;
  params.disableNativeImageDecoder = params.disableNativeImageDecoder === true;
  var CMapReaderFactory = params.CMapReaderFactory || DOMCMapReaderFactory;
  if (!worker) {
    var workerPort = getDefaultSetting('workerPort');
    worker = workerPort ? new PDFWorker(null, workerPort) : new PDFWorker();
    task._worker = worker;
  }
  var docId = task.docId;
  worker.promise.then(function () {
    if (task.destroyed) {
      throw new Error('Loading aborted');
    }
    return _fetchDocument(worker, params, rangeTransport, docId).then(function (workerId) {
      if (task.destroyed) {
        throw new Error('Loading aborted');
      }
      var messageHandler = new MessageHandler(docId, workerId, worker.port);
      var transport = new WorkerTransport(messageHandler, task, rangeTransport, CMapReaderFactory);
      task._transport = transport;
      messageHandler.send('Ready', null);
    });
  }).catch(task._capability.reject);
  return task;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.getFilenameFromUrl"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>getFilenameFromUrl (url)](#apidoc.element.pdfjs-dist.pdf.getFilenameFromUrl)
- description and source-code
```javascript
function getFilenameFromUrl(url) {
  var anchor = url.indexOf('#');
  var query = url.indexOf('?');
  var end = Math.min(anchor > 0 ? anchor : url.length, query > 0 ? query : url.length);
  return url.substring(url.lastIndexOf('/', end) + 1, end);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.isValidUrl"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>isValidUrl (url, allowRelative)](#apidoc.element.pdfjs-dist.pdf.isValidUrl)
- description and source-code
```javascript
function isValidUrl(url, allowRelative) {
  deprecated('isValidUrl(), please use createValidAbsoluteUrl() instead.');
  var baseUrl = allowRelative ? 'http://example.com' : null;
  return createValidAbsoluteUrl(url, baseUrl) !== null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.removeNullCharacters"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>removeNullCharacters (str)](#apidoc.element.pdfjs-dist.pdf.removeNullCharacters)
- description and source-code
```javascript
function removeNullCharacters(str) {
  if (typeof str !== 'string') {
    warn('The argument for removeNullCharacters must be a string.');
    return str;
  }
  return str.replace(NullCharactersRegExp, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.renderTextLayer"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>renderTextLayer (renderParameters)](#apidoc.element.pdfjs-dist.pdf.renderTextLayer)
- description and source-code
```javascript
function renderTextLayer(renderParameters) {
  var task = new TextLayerRenderTask(renderParameters.textContent, renderParameters.container, renderParameters.viewport, renderParameters
.textDivs, renderParameters.enhanceTextSelection);
  task._render(renderParameters.timeout);
  return task;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.pdfjs-dist.pdf.shadow"></a>[function <span class="apidocSignatureSpan">pdfjs-dist.pdf.</span>shadow (obj, prop, value)](#apidoc.element.pdfjs-dist.pdf.shadow)
- description and source-code
```javascript
function shadow(obj, prop, value) {
  Object.defineProperty(obj, prop, {
    value: value,
    enumerable: true,
    configurable: true,
    writable: false
  });
  return value;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
