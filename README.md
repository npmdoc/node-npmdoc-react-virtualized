# api documentation for  [react-virtualized (v9.7.0)](https://github.com/bvaughn/react-virtualized)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-virtualized.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-virtualized) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-virtualized.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-virtualized)
#### React components for efficiently rendering large, scrollable lists and tabular data

[![NPM](https://nodei.co/npm/react-virtualized.png?downloads=true)](https://www.npmjs.com/package/react-virtualized)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-virtualized/build/screenCapture.buildNpmdoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-react-virtualized%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-virtualized/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-virtualized/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-virtualized/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Brian Vaughn",
        "email": "brian.david.vaughn@gmail.com"
    },
    "browserify": {
        "transform": [
            "loose-envify"
        ]
    },
    "bugs": {
        "url": "https://github.com/bvaughn/react-virtualized/issues"
    },
    "dependencies": {
        "babel-runtime": "^6.11.6",
        "classnames": "^2.2.3",
        "dom-helpers": "^2.4.0 || ^3.0.0",
        "loose-envify": "^1.3.0"
    },
    "description": "React components for efficiently rendering large, scrollable lists and tabular data",
    "devDependencies": {
        "autoprefixer": "^6.2.3",
        "babel-cli": "6.8.0",
        "babel-core": "^6.5.1",
        "babel-eslint": "^6.0.4",
        "babel-jest": "^18.0.0",
        "babel-loader": "^6.2.3",
        "babel-plugin-__coverage__": "^0.111111.11",
        "babel-plugin-react-transform": "^2.0.0",
        "babel-plugin-transform-react-inline-elements": "^6.6.5",
        "babel-plugin-transform-react-remove-prop-types": "^0.2.10",
        "babel-plugin-transform-runtime": "^6.15.0",
        "babel-plugin-typecheck": "^3.9.0",
        "babel-polyfill": "^6.5.0",
        "babel-preset-es2015": "6.22.0",
        "babel-preset-es2015-rollup": "3.0.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-1": "^6.5.0",
        "bluebird": "^3.0.5",
        "codecov": "^1.0.1",
        "codemirror": "^5.18.0",
        "cross-env": "^1.0.7",
        "css-loader": "^0.23.0",
        "express": "^4.13.3",
        "extract-text-webpack-plugin": "^1.0.1",
        "file-loader": "^0.8.5",
        "flow-bin": "^0.39.0",
        "fs-extra": "^0.30.0",
        "gh-pages": "^0.11.0",
        "html-webpack-plugin": "^2.16.1",
        "immutable": "^3.7.5",
        "jest": "^18.1.0",
        "postcss": "^5.0.14",
        "postcss-cli": "^2.3.3",
        "postcss-loader": "^0.9.1",
        "raf": "^3.3.0",
        "react": "16.0.0-alpha.2",
        "react-addons-test-utils": "16.0.0-alpha.2",
        "react-codemirror": "^0.2.6",
        "react-dom": "16.0.0-alpha.2",
        "react-router": "^4.0.0-alpha.5",
        "react-transform-catch-errors": "^1.0.2",
        "react-transform-hmr": "^1.0.2",
        "redbox-react": "^1.0.1",
        "rimraf": "^2.4.3",
        "standard": "^7.0.1",
        "style-loader": "^0.13.0",
        "watch": "^0.18.0",
        "webpack": "^1.9.6",
        "webpack-dashboard": "0.0.1",
        "webpack-dev-server": "^1.14.0"
    },
    "directories": {},
    "dist": {
        "shasum": "900ec246666796afabc0f9c9f6ae9764327afb30",
        "tarball": "https://registry.npmjs.org/react-virtualized/-/react-virtualized-9.7.0.tgz"
    },
    "files": [
        "dist",
        "styles.css"
    ],
    "gitHead": "a24c3efae7fb444491414f2a3f82870f4f697a83",
    "homepage": "https://github.com/bvaughn/react-virtualized",
    "jest": {
        "setupFiles": [
            "./source/jest-setup.js"
        ],
        "testPathDirs": [
            "./source"
        ],
        "testRegex": ".jest.js",
        "verbose": true
    },
    "jsnext:main": "dist/es/index.js",
    "keywords": [
        "react",
        "reactjs",
        "react-component",
        "virtual",
        "list",
        "scrolling",
        "infinite",
        "virtualized",
        "table",
        "fixed",
        "header",
        "flex",
        "flexbox",
        "grid",
        "spreadsheet"
    ],
    "license": "MIT",
    "main": "dist/commonjs/index.js",
    "maintainers": [
        {
            "name": "brianvaughn",
            "email": "briandavidvaughn@gmail.com"
        }
    ],
    "module": "dist/es/index.js",
    "name": "react-virtualized",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^15.3.0 || ^16.0.0-alpha",
        "react-dom": "^15.3.0 || ^16.0.0-alpha"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bvaughn/react-virtualized.git"
    },
    "scripts": {
        "build": "npm run build:commonjs && npm run build:css && npm run build:es && npm run build:demo && npm run build:umd",
        "build:commonjs": "npm run clean:commonjs && cross-env NODE_ENV=production cross-env BABEL_ENV=commonjs babel source --out-dir dist/commonjs --ignore *.example.js,*.test.js,source/demo/,source/tests.js",
        "build:css": "postcss --config postcss.config.js --use autoprefixer source/styles.css > styles.css",
        "build:demo": "npm run clean:demo && cross-env NODE_ENV=production webpack --config webpack.config.demo.js -p --bail",
        "build:es": "npm run clean:es && cross-env NODE_ENV=production cross-env BABEL_ENV=es babel source --out-dir dist/es --ignore *.example.js,*.test.js,source/demo/,source/tests.js",
        "build:umd": "npm run clean:umd && cross-env NODE_ENV=production webpack --config webpack.config.umd.js --bail",
        "clean": "npm run clean:commonjs && npm run clean:demo && npm run clean:es && npm run clean:umd",
        "clean:commonjs": "rimraf dist/commonjs",
        "clean:demo": "rimraf build",
        "clean:es": "rimraf dist/es",
        "clean:umd": "rimraf dist/umd",
        "deploy": "gh-pages -d build",
        "lint": "standard",
        "postpublish": "npm run deploy",
        "posttest": "[ -z \"$CI\" ] || codecov",
        "prebuild": "npm run lint",
        "predeploy": "cp ./circle.yml ./build/",
        "prepublish": "npm run build",
        "start": "cross-env NODE_ENV=development webpack-dev-server --hot --inline --config webpack.config.dev.js",
        "test": "npm run lint && npm run test:jest",
        "test:jest": "jest --no-watchman",
        "watch": "watch 'clear && npm run test -s' source",
        "watch:jest": "jest --no-watchman --watch"
    },
    "standard": {
        "parser": "babel-eslint",
        "ignore": [
            "dist",
            "playground",
            "source/vendor"
        ],
        "global": [
            "afterAll",
            "afterEach",
            "beforeAll",
            "beforeEach",
            "describe",
            "expect",
            "fdescribe",
            "fit",
            "getComputedStyle",
            "it",
            "jest",
            "spyOn"
        ]
    },
    "user": "bvaughn",
    "version": "9.7.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-virtualized](#apidoc.module.react-virtualized)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>ArrowKeyStepper (props, context)](#apidoc.element.react-virtualized.ArrowKeyStepper)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>AutoSizer (props)](#apidoc.element.react-virtualized.AutoSizer)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>CellMeasurer (props, context)](#apidoc.element.react-virtualized.CellMeasurer)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>CellMeasurerCache ()](#apidoc.element.react-virtualized.CellMeasurerCache)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>Collection (props, context)](#apidoc.element.react-virtualized.Collection)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>Column ()](#apidoc.element.react-virtualized.Column)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>ColumnSizer (props, context)](#apidoc.element.react-virtualized.ColumnSizer)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>Grid (props, context)](#apidoc.element.react-virtualized.Grid)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>InfiniteLoader (props, context)](#apidoc.element.react-virtualized.InfiniteLoader)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>List (props, context)](#apidoc.element.react-virtualized.List)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>Masonry (props, context)](#apidoc.element.react-virtualized.Masonry)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>MultiGrid (props, context)](#apidoc.element.react-virtualized.MultiGrid)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>ScrollSync (props, context)](#apidoc.element.react-virtualized.ScrollSync)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>SortIndicator (_ref)](#apidoc.element.react-virtualized.SortIndicator)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>Table (props)](#apidoc.element.react-virtualized.Table)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>WindowScroller (props)](#apidoc.element.react-virtualized.WindowScroller)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>accessibilityOverscanIndicesGetter (_ref)](#apidoc.element.react-virtualized.accessibilityOverscanIndicesGetter)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>createMasonryCellPositioner (_ref)](#apidoc.element.react-virtualized.createMasonryCellPositioner)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>defaultCellRangeRenderer (_ref)](#apidoc.element.react-virtualized.defaultCellRangeRenderer)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>defaultOverscanIndicesGetter (_ref)](#apidoc.element.react-virtualized.defaultOverscanIndicesGetter)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>defaultTableCellDataGetter (_ref)](#apidoc.element.react-virtualized.defaultTableCellDataGetter)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>defaultTableCellRenderer (_ref)](#apidoc.element.react-virtualized.defaultTableCellRenderer)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>defaultTableHeaderRenderer (_ref)](#apidoc.element.react-virtualized.defaultTableHeaderRenderer)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>defaultTableHeaderRowRenderer (_ref)](#apidoc.element.react-virtualized.defaultTableHeaderRowRenderer)
1.  [function <span class="apidocSignatureSpan">react-virtualized.</span>defaultTableRowRenderer (_ref)](#apidoc.element.react-virtualized.defaultTableRowRenderer)
1.  object <span class="apidocSignatureSpan">react-virtualized.</span>SortDirection



# <a name="apidoc.module.react-virtualized"></a>[module react-virtualized](#apidoc.module.react-virtualized)

#### <a name="apidoc.element.react-virtualized.ArrowKeyStepper"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>ArrowKeyStepper (props, context)](#apidoc.element.react-virtualized.ArrowKeyStepper)
- description and source-code
```javascript
function ArrowKeyStepper(props, context) {
  _classCallCheck(this, ArrowKeyStepper);

  var _this = _possibleConstructorReturn(this, (ArrowKeyStepper.__proto__ || Object.getPrototypeOf(ArrowKeyStepper)).call(this,
props, context));

  _this.state = {
    scrollToColumn: props.scrollToColumn,
    scrollToRow: props.scrollToRow
  };

  _this._columnStartIndex = 0;
  _this._columnStopIndex = 0;
  _this._rowStartIndex = 0;
  _this._rowStopIndex = 0;

  _this._onKeyDown = _this._onKeyDown.bind(_this);
  _this._onSectionRendered = _this._onSectionRendered.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.AutoSizer"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>AutoSizer (props)](#apidoc.element.react-virtualized.AutoSizer)
- description and source-code
```javascript
function AutoSizer(props) {
  _classCallCheck(this, AutoSizer);

  var _this = _possibleConstructorReturn(this, (AutoSizer.__proto__ || Object.getPrototypeOf(AutoSizer)).call(this, props));

  _this.state = {
    height: 0,
    width: 0
  };

  _this._onResize = _this._onResize.bind(_this);
  _this._setRef = _this._setRef.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.CellMeasurer"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>CellMeasurer (props, context)](#apidoc.element.react-virtualized.CellMeasurer)
- description and source-code
```javascript
function CellMeasurer(props, context) {
  _classCallCheck(this, CellMeasurer);

  var _this = _possibleConstructorReturn(this, (CellMeasurer.__proto__ || Object.getPrototypeOf(CellMeasurer)).call(this, props,
context));

  _this._measure = _this._measure.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.CellMeasurerCache"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>CellMeasurerCache ()](#apidoc.element.react-virtualized.CellMeasurerCache)
- description and source-code
```javascript
function CellMeasurerCache() {
  var _this = this;

  var params = arguments.length > 0 && arguments[0] !== undefined ? arguments[0] : {};

  _classCallCheck(this, CellMeasurerCache);

  this.columnWidth = function (_ref) {
    var index = _ref.index;

    var key = _this._keyMapper(0, index);

    return _this._columnWidthCache.hasOwnProperty(key) ? _this._columnWidthCache[key] : _this._defaultWidth;
  };

  this.rowHeight = function (_ref2) {
    var index = _ref2.index;

    var key = _this._keyMapper(index, 0);

    return _this._rowHeightCache.hasOwnProperty(key) ? _this._rowHeightCache[key] : _this._defaultHeight;
  };

  var defaultHeight = params.defaultHeight,
      defaultWidth = params.defaultWidth,
      fixedHeight = params.fixedHeight,
      fixedWidth = params.fixedWidth,
      keyMapper = params.keyMapper,
      minHeight = params.minHeight,
      minWidth = params.minWidth;


  this._hasFixedHeight = fixedHeight === true;
  this._hasFixedWidth = fixedWidth === true;
  this._minHeight = minHeight || 0;
  this._minWidth = minWidth || 0;
  this._keyMapper = keyMapper || defaultKeyMapper;

  this._defaultHeight = Math.max(this._minHeight, typeof defaultHeight === 'number' ? defaultHeight : DEFAULT_HEIGHT);
  this._defaultWidth = Math.max(this._minWidth, typeof defaultWidth === 'number' ? defaultWidth : DEFAULT_WIDTH);

  if (process.env.NODE_ENV !== 'production') {
    if (this._hasFixedHeight === false && this._hasFixedWidth === false) {
      console.warn('CellMeasurerCache should only measure a cell\'s width or height. ' + 'You have configured CellMeasurerCache
to measure both. ' + 'This will result in poor performance.');
    }

    if (this._hasFixedHeight === false && this._defaultHeight === 0) {
      console.warn('Fixed height CellMeasurerCache should specify a :defaultHeight greater than 0. ' + 'Failing to do so will lead
 to unnecessary layout and poor performance.');
    }

    if (this._hasFixedWidth === false && this._defaultWidth === 0) {
      console.warn('Fixed width CellMeasurerCache should specify a :defaultWidth greater than 0. ' + 'Failing to do so will lead
 to unnecessary layout and poor performance.');
    }
  }

  this._columnCount = 0;
  this._rowCount = 0;

  this._cellHeightCache = {};
  this._cellWidthCache = {};
  this._columnWidthCache = {};
  this._rowHeightCache = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.Collection"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>Collection (props, context)](#apidoc.element.react-virtualized.Collection)
- description and source-code
```javascript
function Collection(props, context) {
  _classCallCheck(this, Collection);

  var _this = _possibleConstructorReturn(this, (Collection.__proto__ || Object.getPrototypeOf(Collection)).call(this, props, context
));

  _this._cellMetadata = [];
  _this._lastRenderedCellIndices = [];

  // Cell cache during scroll (for perforamnce)
  _this._cellCache = [];

  _this._isScrollingChange = _this._isScrollingChange.bind(_this);
  _this._setCollectionViewRef = _this._setCollectionViewRef.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.Column"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>Column ()](#apidoc.element.react-virtualized.Column)
- description and source-code
```javascript
function Column() {
  _classCallCheck(this, Column);

  return _possibleConstructorReturn(this, (Column.__proto__ || Object.getPrototypeOf(Column)).apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.ColumnSizer"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>ColumnSizer (props, context)](#apidoc.element.react-virtualized.ColumnSizer)
- description and source-code
```javascript
function ColumnSizer(props, context) {
  _classCallCheck(this, ColumnSizer);

  var _this = _possibleConstructorReturn(this, (ColumnSizer.__proto__ || Object.getPrototypeOf(ColumnSizer)).call(this, props, context
));

  _this._registerChild = _this._registerChild.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.Grid"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>Grid (props, context)](#apidoc.element.react-virtualized.Grid)
- description and source-code
```javascript
function Grid(props, context) {
  _classCallCheck(this, Grid);

  var _this = _possibleConstructorReturn(this, (Grid.__proto__ || Object.getPrototypeOf(Grid)).call(this, props, context));

  _this.state = {
    isScrolling: false,
    scrollDirectionHorizontal: _defaultOverscanIndicesGetter.SCROLL_DIRECTION_FORWARD,
    scrollDirectionVertical: _defaultOverscanIndicesGetter.SCROLL_DIRECTION_FORWARD,
    scrollLeft: 0,
    scrollTop: 0
  };

  // Invokes onSectionRendered callback only when start/stop row or column indices change
  _this._onGridRenderedMemoizer = (0, _createCallbackMemoizer2.default)();
  _this._onScrollMemoizer = (0, _createCallbackMemoizer2.default)(false);

  // Bind functions to instance so they don't lose context when passed around
  _this._debounceScrollEndedCallback = _this._debounceScrollEndedCallback.bind(_this);
  _this._invokeOnGridRenderedHelper = _this._invokeOnGridRenderedHelper.bind(_this);
  _this._onScroll = _this._onScroll.bind(_this);
  _this._setScrollingContainerRef = _this._setScrollingContainerRef.bind(_this);

  _this._columnWidthGetter = _this._wrapSizeGetter(props.columnWidth);
  _this._rowHeightGetter = _this._wrapSizeGetter(props.rowHeight);

  _this._deferredInvalidateColumnIndex = null;
  _this._deferredInvalidateRowIndex = null;
  _this._recomputeScrollLeftFlag = false;
  _this._recomputeScrollTopFlag = false;

  var deferredMeasurementCache = props.deferredMeasurementCache;
  var deferredMode = typeof deferredMeasurementCache !== 'undefined';

  _this._columnSizeAndPositionManager = new _ScalingCellSizeAndPositionManager2.default({
    batchAllCells: deferredMode && !deferredMeasurementCache.hasFixedHeight(),
    cellCount: props.columnCount,
    cellSizeGetter: function cellSizeGetter(params) {
      return _this._columnWidthGetter(params);
    },
    estimatedCellSize: _this._getEstimatedColumnSize(props)
  });
  _this._rowSizeAndPositionManager = new _ScalingCellSizeAndPositionManager2.default({
    batchAllCells: deferredMode && !deferredMeasurementCache.hasFixedWidth(),
    cellCount: props.rowCount,
    cellSizeGetter: function cellSizeGetter(params) {
      return _this._rowHeightGetter(params);
    },
    estimatedCellSize: _this._getEstimatedRowSize(props)
  });

  // See defaultCellRangeRenderer() for more information on the usage of these caches
  _this._cellCache = {};
  _this._styleCache = {};
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.InfiniteLoader"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>InfiniteLoader (props, context)](#apidoc.element.react-virtualized.InfiniteLoader)
- description and source-code
```javascript
function InfiniteLoader(props, context) {
  _classCallCheck(this, InfiniteLoader);

  var _this = _possibleConstructorReturn(this, (InfiniteLoader.__proto__ || Object.getPrototypeOf(InfiniteLoader)).call(this, props
, context));

  _this._loadMoreRowsMemoizer = (0, _createCallbackMemoizer2.default)();

  _this._onRowsRendered = _this._onRowsRendered.bind(_this);
  _this._registerChild = _this._registerChild.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.List"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>List (props, context)](#apidoc.element.react-virtualized.List)
- description and source-code
```javascript
function List(props, context) {
  _classCallCheck(this, List);

  var _this = _possibleConstructorReturn(this, (List.__proto__ || Object.getPrototypeOf(List)).call(this, props, context));

  _this._cellRenderer = _this._cellRenderer.bind(_this);
  _this._onScroll = _this._onScroll.bind(_this);
  _this._onSectionRendered = _this._onSectionRendered.bind(_this);
  _this._setRef = _this._setRef.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.Masonry"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>Masonry (props, context)](#apidoc.element.react-virtualized.Masonry)
- description and source-code
```javascript
function Masonry(props, context) {
  _classCallCheck(this, Masonry);

  var _this = _possibleConstructorReturn(this, (Masonry.__proto__ || Object.getPrototypeOf(Masonry)).call(this, props, context));

  _this._invalidateOnUpdateStartIndex = null;
  _this._invalidateOnUpdateStopIndex = null;
  _this._positionCache = new _PositionCache2.default();
  _this._startIndex = null;
  _this._startIndexMemoized = null;
  _this._stopIndex = null;
  _this._stopIndexMemoized = null;


  _this.state = {
    isScrolling: false,
    scrollTop: 0
  };

  _this._debounceResetIsScrollingCallback = _this._debounceResetIsScrollingCallback.bind(_this);
  _this._setScrollingContainerRef = _this._setScrollingContainerRef.bind(_this);
  _this._onScroll = _this._onScroll.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.MultiGrid"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>MultiGrid (props, context)](#apidoc.element.react-virtualized.MultiGrid)
- description and source-code
```javascript
function MultiGrid(props, context) {
  _classCallCheck(this, MultiGrid);

  var _this = _possibleConstructorReturn(this, (MultiGrid.__proto__ || Object.getPrototypeOf(MultiGrid)).call(this, props, context
));

  _this.state = {
    scrollLeft: 0,
    scrollTop: 0
  };

  _this._deferredInvalidateColumnIndex = null;
  _this._deferredInvalidateRowIndex = null;

  _this._bottomLeftGridRef = _this._bottomLeftGridRef.bind(_this);
  _this._bottomRightGridRef = _this._bottomRightGridRef.bind(_this);
  _this._cellRendererBottomLeftGrid = _this._cellRendererBottomLeftGrid.bind(_this);
  _this._cellRendererBottomRightGrid = _this._cellRendererBottomRightGrid.bind(_this);
  _this._cellRendererTopRightGrid = _this._cellRendererTopRightGrid.bind(_this);
  _this._columnWidthRightGrid = _this._columnWidthRightGrid.bind(_this);
  _this._onScroll = _this._onScroll.bind(_this);
  _this._rowHeightBottomGrid = _this._rowHeightBottomGrid.bind(_this);
  _this._topLeftGridRef = _this._topLeftGridRef.bind(_this);
  _this._topRightGridRef = _this._topRightGridRef.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.ScrollSync"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>ScrollSync (props, context)](#apidoc.element.react-virtualized.ScrollSync)
- description and source-code
```javascript
function ScrollSync(props, context) {
  _classCallCheck(this, ScrollSync);

  var _this = _possibleConstructorReturn(this, (ScrollSync.__proto__ || Object.getPrototypeOf(ScrollSync)).call(this, props, context
));

  _this.state = {
    clientHeight: 0,
    clientWidth: 0,
    scrollHeight: 0,
    scrollLeft: 0,
    scrollTop: 0,
    scrollWidth: 0
  };

  _this._onScroll = _this._onScroll.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.SortIndicator"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>SortIndicator (_ref)](#apidoc.element.react-virtualized.SortIndicator)
- description and source-code
```javascript
function SortIndicator(_ref) {
  var sortDirection = _ref.sortDirection;

  var classNames = (0, _classnames2.default)('ReactVirtualized__Table__sortableHeaderIcon', {
    'ReactVirtualized__Table__sortableHeaderIcon--ASC': sortDirection === _SortDirection2.default.ASC,
    'ReactVirtualized__Table__sortableHeaderIcon--DESC': sortDirection === _SortDirection2.default.DESC
  });

  return _react2.default.createElement(
    'svg',
    {
      className: classNames,
      width: 18,
      height: 18,
      viewBox: '0 0 24 24'
    },
    sortDirection === _SortDirection2.default.ASC ? _react2.default.createElement('path', { d: 'M7 14l5-5 5 5z' }) : _react2.default
.createElement('path', { d: 'M7 10l5 5 5-5z' }),
    _react2.default.createElement('path', { d: 'M0 0h24v24H0z', fill: 'none' })
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.Table"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>Table (props)](#apidoc.element.react-virtualized.Table)
- description and source-code
```javascript
function Table(props) {
  _classCallCheck(this, Table);

  var _this = _possibleConstructorReturn(this, (Table.__proto__ || Object.getPrototypeOf(Table)).call(this, props));

  _this.state = {
    scrollbarWidth: 0
  };

  _this._createColumn = _this._createColumn.bind(_this);
  _this._createRow = _this._createRow.bind(_this);
  _this._onScroll = _this._onScroll.bind(_this);
  _this._onSectionRendered = _this._onSectionRendered.bind(_this);
  _this._setRef = _this._setRef.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.WindowScroller"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>WindowScroller (props)](#apidoc.element.react-virtualized.WindowScroller)
- description and source-code
```javascript
function WindowScroller(props) {
  _classCallCheck(this, WindowScroller);

  // Handle server-side rendering case
  var _this = _possibleConstructorReturn(this, (WindowScroller.__proto__ || Object.getPrototypeOf(WindowScroller)).call(this, props
));

  var _ref = typeof window !== 'undefined' ? (0, _dimensions.getDimensions)(props.scrollElement || window) : { width: 0, height:
0 },
      width = _ref.width,
      height = _ref.height;

  _this.state = {
    height: height,
    width: width,
    isScrolling: false,
    scrollLeft: 0,
    scrollTop: 0
  };

  _this._onResize = _this._onResize.bind(_this);
  _this.__handleWindowScrollEvent = _this.__handleWindowScrollEvent.bind(_this);
  _this.__resetIsScrolling = _this.__resetIsScrolling.bind(_this);
  return _this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.accessibilityOverscanIndicesGetter"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>accessibilityOverscanIndicesGetter (_ref)](#apidoc.element.react-virtualized.accessibilityOverscanIndicesGetter)
- description and source-code
```javascript
function defaultOverscanIndicesGetter(_ref) {
  var direction = _ref.direction,
      cellCount = _ref.cellCount,
      overscanCellsCount = _ref.overscanCellsCount,
      scrollDirection = _ref.scrollDirection,
      startIndex = _ref.startIndex,
      stopIndex = _ref.stopIndex;

  var overscanStartIndex = void 0;
  var overscanStopIndex = void 0;

  // Make sure we render at least 1 cell extra before and after (except near boundaries)
  // This is necessary in order to support keyboard navigation (TAB/SHIFT+TAB) in some cases
  // For more info see issues #625
  overscanCellsCount = Math.max(1, overscanCellsCount);

  switch (scrollDirection) {
    case SCROLL_DIRECTION_FORWARD:
      overscanStartIndex = startIndex - 1;
      overscanStopIndex = stopIndex + overscanCellsCount;
      break;
    case SCROLL_DIRECTION_BACKWARD:
      overscanStartIndex = startIndex - overscanCellsCount;
      overscanStopIndex = stopIndex + 1;
      break;
  }

  return {
    overscanStartIndex: Math.max(0, overscanStartIndex),
    overscanStopIndex: Math.min(cellCount - 1, overscanStopIndex)
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.createMasonryCellPositioner"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>createMasonryCellPositioner (_ref)](#apidoc.element.react-virtualized.createMasonryCellPositioner)
- description and source-code
```javascript
function createCellPositioner(_ref) {
  var cellMeasurerCache = _ref.cellMeasurerCache,
      columnCount = _ref.columnCount,
      columnWidth = _ref.columnWidth,
      _ref$spacer = _ref.spacer,
      spacer = _ref$spacer === undefined ? 0 : _ref$spacer;

  var columnHeights = void 0;

  initOrResetDerivedValues();

  function cellPositioner(index) {
    // Find the shortest column and use it.
    var columnIndex = 0;
    for (var i = 1; i < columnHeights.length; i++) {
      if (columnHeights[i] < columnHeights[columnIndex]) {
        columnIndex = i;
      }
    }

    var left = columnIndex * (columnWidth + spacer);
    var top = columnHeights[columnIndex] || 0;

    columnHeights[columnIndex] = top + cellMeasurerCache.getHeight(index) + spacer;

    return {
      left: left,
      top: top
    };
  }

  function initOrResetDerivedValues() {
    // Track the height of each column.
    // Layout algorithm below always inserts into the shortest column.
    columnHeights = [];
    for (var i = 0; i < columnCount; i++) {
      columnHeights[i] = 0;
    }
  }

  function reset(params) {
    columnCount = params.columnCount;
    columnWidth = params.columnWidth;
    spacer = params.spacer;

    initOrResetDerivedValues();
  }

  cellPositioner.reset = reset;

  return cellPositioner;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.defaultCellRangeRenderer"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>defaultCellRangeRenderer (_ref)](#apidoc.element.react-virtualized.defaultCellRangeRenderer)
- description and source-code
```javascript
function defaultCellRangeRenderer(_ref) {
  var cellCache = _ref.cellCache,
      cellRenderer = _ref.cellRenderer,
      columnSizeAndPositionManager = _ref.columnSizeAndPositionManager,
      columnStartIndex = _ref.columnStartIndex,
      columnStopIndex = _ref.columnStopIndex,
      deferredMeasurementCache = _ref.deferredMeasurementCache,
      horizontalOffsetAdjustment = _ref.horizontalOffsetAdjustment,
      isScrolling = _ref.isScrolling,
      parent = _ref.parent,
      rowSizeAndPositionManager = _ref.rowSizeAndPositionManager,
      rowStartIndex = _ref.rowStartIndex,
      rowStopIndex = _ref.rowStopIndex,
      scrollLeft = _ref.scrollLeft,
      scrollTop = _ref.scrollTop,
      styleCache = _ref.styleCache,
      verticalOffsetAdjustment = _ref.verticalOffsetAdjustment,
      visibleColumnIndices = _ref.visibleColumnIndices,
      visibleRowIndices = _ref.visibleRowIndices;

  var deferredMode = typeof deferredMeasurementCache !== 'undefined';

  var renderedCells = [];

  // Browsers have native size limits for elements (eg Chrome 33M pixels, IE 1.5M pixes).
  // User cannot scroll beyond these size limitations.
  // In order to work around this, ScalingCellSizeAndPositionManager compresses offsets.
  // We should never cache styles for compressed offsets though as this can lead to bugs.
  // See issue #576 for more.
  var areOffsetsAdjusted = columnSizeAndPositionManager.areOffsetsAdjusted() || rowSizeAndPositionManager.areOffsetsAdjusted();

  var canCacheStyle = !isScrolling || !areOffsetsAdjusted;

  for (var rowIndex = rowStartIndex; rowIndex <= rowStopIndex; rowIndex++) {
    var rowDatum = rowSizeAndPositionManager.getSizeAndPositionOfCell(rowIndex);

    for (var columnIndex = columnStartIndex; columnIndex <= columnStopIndex; columnIndex++) {
      var columnDatum = columnSizeAndPositionManager.getSizeAndPositionOfCell(columnIndex);
      var isVisible = columnIndex >= visibleColumnIndices.start && columnIndex <= visibleColumnIndices.stop && rowIndex >= visibleRowIndices
.start && rowIndex <= visibleRowIndices.stop;
      var key = rowIndex + '-' + columnIndex;
      var style = void 0;

      // Cache style objects so shallow-compare doesn't re-render unnecessarily.
      if (canCacheStyle && styleCache[key]) {
        style = styleCache[key];
      } else {
        // In deferred mode, cells will be initially rendered before we know their size.
        // Don't interfere with CellMeasurer's measurements by setting an invalid size.
        if (deferredMode && !deferredMeasurementCache.has(rowIndex, columnIndex)) {
          // Position not-yet-measured cells at top/left 0,0,
          // And give them width/height of 'auto' so they can grow larger than the parent Grid if necessary.
          // Positioning them further to the right/bottom influences their measured size.
          style = {
            height: 'auto',
            left: 0,
            position: 'absolute',
            top: 0,
            width: 'auto'
          };
        } else {
          style = {
            height: rowDatum.size,
            left: columnDatum.offset + horizontalOffsetAdjustment,
            position: 'absolute',
            top: rowDatum.offset + verticalOffsetAdjustment,
            width: columnDatum.size
          };

          styleCache[key] = style;
        }
      }

      var cellRendererParams = {
        columnIndex: columnIndex,
        isScrolling: isScrolling,
        isVisible: isVisible,
        key: key,
        parent: parent,
        rowIndex: rowIndex,
        style: style
      };

      var renderedCell = void 0;

      // Avoid re-creating cells while scrolling.
      // This can lead to the same cell being created many times and can cause performance issues for "heavy" cells.
      // If a scroll is in progress- cache and reuse cells.
      // This cache will be thrown away once scrolling completes.
      // However if we are scaling scroll positions and sizes, we should also avoid caching.
      // This is because the offset changes slightly as scroll position changes and caching lead ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.defaultOverscanIndicesGetter"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>defaultOverscanIndicesGetter (_ref)](#apidoc.element.react-virtualized.defaultOverscanIndicesGetter)
- description and source-code
```javascript
function defaultOverscanIndicesGetter(_ref) {
  var direction = _ref.direction,
      cellCount = _ref.cellCount,
      overscanCellsCount = _ref.overscanCellsCount,
      scrollDirection = _ref.scrollDirection,
      startIndex = _ref.startIndex,
      stopIndex = _ref.stopIndex;

  var overscanStartIndex = void 0;
  var overscanStopIndex = void 0;

  switch (scrollDirection) {
    case SCROLL_DIRECTION_FORWARD:
      overscanStartIndex = startIndex;
      overscanStopIndex = stopIndex + overscanCellsCount;
      break;
    case SCROLL_DIRECTION_BACKWARD:
      overscanStartIndex = startIndex - overscanCellsCount;
      overscanStopIndex = stopIndex;
      break;
  }

  return {
    overscanStartIndex: Math.max(0, overscanStartIndex),
    overscanStopIndex: Math.min(cellCount - 1, overscanStopIndex)
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.defaultTableCellDataGetter"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>defaultTableCellDataGetter (_ref)](#apidoc.element.react-virtualized.defaultTableCellDataGetter)
- description and source-code
```javascript
function defaultCellDataGetter(_ref) {
  var columnData = _ref.columnData,
      dataKey = _ref.dataKey,
      rowData = _ref.rowData;

  if (typeof rowData.get === 'function') {
    return rowData.get(dataKey);
  } else {
    return rowData[dataKey];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.defaultTableCellRenderer"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>defaultTableCellRenderer (_ref)](#apidoc.element.react-virtualized.defaultTableCellRenderer)
- description and source-code
```javascript
function defaultCellRenderer(_ref) {
  var cellData = _ref.cellData,
      columnData = _ref.columnData,
      dataKey = _ref.dataKey,
      rowData = _ref.rowData,
      rowIndex = _ref.rowIndex;

  if (cellData == null) {
    return '';
  } else {
    return String(cellData);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.defaultTableHeaderRenderer"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>defaultTableHeaderRenderer (_ref)](#apidoc.element.react-virtualized.defaultTableHeaderRenderer)
- description and source-code
```javascript
function defaultHeaderRenderer(_ref) {
  var columnData = _ref.columnData,
      dataKey = _ref.dataKey,
      disableSort = _ref.disableSort,
      label = _ref.label,
      sortBy = _ref.sortBy,
      sortDirection = _ref.sortDirection;

  var showSortIndicator = sortBy === dataKey;
  var children = [_react2.default.createElement(
    'span',
    {
      className: 'ReactVirtualized__Table__headerTruncatedText',
      key: 'label',
      title: label
    },
    label
  )];

  if (showSortIndicator) {
    children.push(_react2.default.createElement(_SortIndicator2.default, {
      key: 'SortIndicator',
      sortDirection: sortDirection
    }));
  }

  return children;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.defaultTableHeaderRowRenderer"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>defaultTableHeaderRowRenderer (_ref)](#apidoc.element.react-virtualized.defaultTableHeaderRowRenderer)
- description and source-code
```javascript
function defaultHeaderRowRenderer(_ref) {
  var className = _ref.className,
      columns = _ref.columns,
      style = _ref.style;

  return _react2.default.createElement(
    'div',
    {
      className: className,
      role: 'row',
      style: style
    },
    columns
  );
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-virtualized.defaultTableRowRenderer"></a>[function <span class="apidocSignatureSpan">react-virtualized.</span>defaultTableRowRenderer (_ref)](#apidoc.element.react-virtualized.defaultTableRowRenderer)
- description and source-code
```javascript
function defaultRowRenderer(_ref) {
  var className = _ref.className,
      columns = _ref.columns,
      index = _ref.index,
      isScrolling = _ref.isScrolling,
      key = _ref.key,
      onRowClick = _ref.onRowClick,
      onRowDoubleClick = _ref.onRowDoubleClick,
      onRowMouseOver = _ref.onRowMouseOver,
      onRowMouseOut = _ref.onRowMouseOut,
      rowData = _ref.rowData,
      style = _ref.style;

  var a11yProps = {};

  if (onRowClick || onRowDoubleClick || onRowMouseOver || onRowMouseOut) {
    a11yProps['aria-label'] = 'row';
    a11yProps.tabIndex = 0;

    if (onRowClick) {
      a11yProps.onClick = function (event) {
        return onRowClick({ event: event, index: index, rowData: rowData });
      };
    }
    if (onRowDoubleClick) {
      a11yProps.onDoubleClick = function (event) {
        return onRowDoubleClick({ event: event, index: index, rowData: rowData });
      };
    }
    if (onRowMouseOut) {
      a11yProps.onMouseOut = function (event) {
        return onRowMouseOut({ event: event, index: index, rowData: rowData });
      };
    }
    if (onRowMouseOver) {
      a11yProps.onMouseOver = function (event) {
        return onRowMouseOver({ event: event, index: index, rowData: rowData });
      };
    }
  }

  return _react2.default.createElement(
    'div',
    _extends({}, a11yProps, {
      className: className,
      key: key,
      role: 'row',
      style: style
    }),
    columns
  );
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
