## 6.0.1 (2023-06-05)


### Bug Fixes

* "X" is not a valid hex prefix for char references ([465038b](https://github.com/rubensworks/saxes/commit/465038bd381a84ea8cbfa5d65f4fbe77a2bd6e04))
* add fragment and additionalNamespaces to SaxesOption typing ([02d8275](https://github.com/rubensworks/saxes/commit/02d8275f3b3178210ed249b68b18e058436b144b))
* add namespace checks ([9f94c4b](https://github.com/rubensworks/saxes/commit/9f94c4b7fae81d5c2082c0b72026bedf4b5c8a84))
* always run in strict mode ([ed8b0b1](https://github.com/rubensworks/saxes/commit/ed8b0b168d6858c2687abe16af07fa9770e70f82))
* CDATA end in attributes must not cause an error ([a7495ac](https://github.com/rubensworks/saxes/commit/a7495ac448a23e154291a10c611f841068c704c5))
* check that the characters we read are valid char data ([7611a85](https://github.com/rubensworks/saxes/commit/7611a85ceeb0f2ef05ad04eda3f593d3fb193f6a))
* correct typo ([97bc5da](https://github.com/rubensworks/saxes/commit/97bc5da05b19263264e79679e3f872980381948d))
* detect unclosed tags in fragments ([5642f36](https://github.com/rubensworks/saxes/commit/5642f36265b949aa539d45bc554191eb188a8adc))
* disallow BOM characters at the beginning of subsequent chunks ([66d07b6](https://github.com/rubensworks/saxes/commit/66d07b64ea7fb066b1531575706b13eec3899a40))
* disallow spaces after open waka ([da7f76d](https://github.com/rubensworks/saxes/commit/da7f76d6ccab1e9ead040c749c9d177f204367b4))
* don't serialize the fileName as undefined: when not present ([4ff2365](https://github.com/rubensworks/saxes/commit/4ff2365ce63eea44a5226f8bdb69deb0505e279e))
* drop the lowercase option ([987d4bf](https://github.com/rubensworks/saxes/commit/987d4bfbc6b2faaf93dd9db327e50b0c812b11e4))
* emit CDATA on empty CDATA section too ([95d192f](https://github.com/rubensworks/saxes/commit/95d192f888c3cbacc0d133ad4328cf5601031f85))
* emit empty comment ([b3db392](https://github.com/rubensworks/saxes/commit/b3db3921e43584cbfe576663222f3f3b1acd1790))
* entities are always strict ([0f6a30e](https://github.com/rubensworks/saxes/commit/0f6a30e7e62de4901c6b2778d1f3d9e818bd0b8c))
* fail on colon at start of QName ([507addd](https://github.com/rubensworks/saxes/commit/507addd20890a2e615ef0b3f71af453b81714cd5))
* fix a bug in EOL handling ([bed38a8](https://github.com/rubensworks/saxes/commit/bed38a841913ba5c7917624f1f36254560042936))
* fix bug with initial eol characters ([7b3db75](https://github.com/rubensworks/saxes/commit/7b3db7596ff581d719d0d02ca0f4a7ddbff2ea77))
* fix corrupted attribute values when there is no text handler ([e135f11](https://github.com/rubensworks/saxes/commit/e135f11be7dfb5f8f13d6e0227bd25f0be7b9295)), closes [#38](https://github.com/rubensworks/saxes/issues/38)
* fix some typing mistakes ([f2a1d5e](https://github.com/rubensworks/saxes/commit/f2a1d5e5d27e2cf40e45b9e8a573007d7d20e37f))
* fixing linting errors for eslint 8 ([cd4b5c9](https://github.com/rubensworks/saxes/commit/cd4b5c9ddf166d426ece77349bbde7538fb0aaa4))
* generate an error on prefix with empty local name ([89a3b86](https://github.com/rubensworks/saxes/commit/89a3b86a09806080768f92c80a9b9cb151d89906)), closes [#5](https://github.com/rubensworks/saxes/issues/5)
* handle column computation over characters in the astral plane ([cefc8f7](https://github.com/rubensworks/saxes/commit/cefc8f7e2a9a78f2abcae9385a3c9f8528cb4276))
* handling of end of line characters ([f13247a](https://github.com/rubensworks/saxes/commit/f13247a1e5dfdd60a5cd3e867c152b75364ae8cf))
* harmonize error messages and initialize flags ([9a20cad](https://github.com/rubensworks/saxes/commit/9a20cad371f0f32b6d35f8b0f03978ab68b56aa5))
* implement attribute normalization ([be51114](https://github.com/rubensworks/saxes/commit/be51114635d0cb24d1b8a0a1001f02291211401a)), closes [#24](https://github.com/rubensworks/saxes/issues/24)
* just one error for text before the root, and text after ([101ea50](https://github.com/rubensworks/saxes/commit/101ea50e36b5e8e12f86f2980e332bf83c8ec6f5))
* more namespace checks ([a1add21](https://github.com/rubensworks/saxes/commit/a1add21aa3b716e62038d96026f5496f6db43ed5))
* move eslint to devDependencies ([d747538](https://github.com/rubensworks/saxes/commit/d747538b766a0d9e53b75e399acf31f46fcd44de))
* move namespace checks to their proper place ([4a1c99f](https://github.com/rubensworks/saxes/commit/4a1c99f197ec197e9844abf08e886852c824864a))
* normalize \r\n and \r followed by something else to \n ([d7b1abe](https://github.com/rubensworks/saxes/commit/d7b1abea6c5ce8826757aacdca24ed6e289f1c19)), closes [#2](https://github.com/rubensworks/saxes/issues/2)
* npm audit warning ([a6c9ba8](https://github.com/rubensworks/saxes/commit/a6c9ba83486404677dfd4aa107f3356d21e455a8))
* only accept uppercase CDATA to mark the start of CDATA ([e86534d](https://github.com/rubensworks/saxes/commit/e86534ddcc3b5e8e78228c68d5f29fdc4f768eff))
* pay attention to comments and processing instructions in DTDs ([52ffd90](https://github.com/rubensworks/saxes/commit/52ffd903e9e78e30aa38392b008e3f172b9c977c)), closes [#19](https://github.com/rubensworks/saxes/issues/19)
* prevent colons in pi and entity names when xmlns is true ([4327eec](https://github.com/rubensworks/saxes/commit/4327eec497301a1787268a05341103e88d879bea))
* prevent empty entities ([04e1593](https://github.com/rubensworks/saxes/commit/04e1593a2a0702752907cee4d5c7c05a02a17ba1))
* raise an error if the document does not have a root ([f2de520](https://github.com/rubensworks/saxes/commit/f2de52026f8d4326b2b5029e1019071a68bbb9b7))
* raise an error on ]]> in character data ([2964381](https://github.com/rubensworks/saxes/commit/2964381eb157a22bca8f0bf270632e4d2137e03b))
* raise an error on < in attribute values ([4fd67a1](https://github.com/rubensworks/saxes/commit/4fd67a17c00b89136eba1ef74fbba2ddc5508246))
* raise an error on multiple root elements ([45047ae](https://github.com/rubensworks/saxes/commit/45047ae97b4dfc62da8782e9413348880e92d09e))
* raise error on CDATA before or after root ([604241f](https://github.com/rubensworks/saxes/commit/604241fc92f3b48d7d310610d2c1ba27ecd7f81d))
* raise error on character reference outside CHAR production ([30fb540](https://github.com/rubensworks/saxes/commit/30fb540fd54d43f4fb349ff820a1b786d0fecaf3))
* remove broken or pointless examples ([1a5b642](https://github.com/rubensworks/saxes/commit/1a5b6426f243c29b324a89e1b5ecb484b7be7f4c))
* report an error on duplicate attributes ([ee4e340](https://github.com/rubensworks/saxes/commit/ee4e3403536e79d19932743871a24af52f50a71d))
* report an error on whitespace at the start of end tag ([c13b122](https://github.com/rubensworks/saxes/commit/c13b122a57b068eea88e537df03b216370f25132))
* report processing instructions that do not have a target ([c007e39](https://github.com/rubensworks/saxes/commit/c007e3915d5d6b81d90ffa1abf1b3343ec6449b0))
* resolve is now part of the public API ([bb4bed5](https://github.com/rubensworks/saxes/commit/bb4bed5c764ac460519f9a94e3518d9956605eb8))
* treat ?? in processing instructions correctly ([bc1e1d4](https://github.com/rubensworks/saxes/commit/bc1e1d4d192831fbb07ec35a4fcb1f818ce4c5a0))
* trim URIs ([78cc6f3](https://github.com/rubensworks/saxes/commit/78cc6f3f5db8f28c5dd80ffe12f3770bb989a86f))
* **typings:** "selfClosing" => "isSelfClosing" ([d96a2bd](https://github.com/rubensworks/saxes/commit/d96a2bd0c29016efdfa7a05d3443f3e363a2ac73))
* use `isNameChar` for later chars in PI target ([83d2b61](https://github.com/rubensworks/saxes/commit/83d2b610f7c0c628537b1754a145ce5b0edfef47))
* use the latest xmlchars ([b30a714](https://github.com/rubensworks/saxes/commit/b30a714ced99b9c1665971a3b6ca5f9dd484d12b))
* use xmlchars for checking names ([2c939fe](https://github.com/rubensworks/saxes/commit/2c939feee504e071cadc1528594f4088bb7c440f))
* verify that character references match the CHAR production ([369afde](https://github.com/rubensworks/saxes/commit/369afde77269316594e05595aac1a78cdfe9b278))
* we don't support node 10 anymore ([f2aa1a8](https://github.com/rubensworks/saxes/commit/f2aa1a8e2b379f102010b9c552490f385f7854af))


### Code Refactoring

* adjust the names used for processing instructions ([3b508e9](https://github.com/rubensworks/saxes/commit/3b508e930e79afa856d6f607ec774d69b1790fa6))
* convert code to ES6 ([fe81170](https://github.com/rubensworks/saxes/commit/fe81170978b068e44020a0748f4d001b49aafe7d))
* drop attribute event ([c7c2e80](https://github.com/rubensworks/saxes/commit/c7c2e801c84fdd0fe458e4910f6478dabd98b406))
* drop buffer size checks ([9ce2f7a](https://github.com/rubensworks/saxes/commit/9ce2f7a25c78635bc69a7d8fa10672a8983322a5))
* drop normalize ([9c6d84c](https://github.com/rubensworks/saxes/commit/9c6d84cef17f37314aabf6a0c068ddb32d0bd856))
* drop opencdata and on closecdata ([3287d2c](https://github.com/rubensworks/saxes/commit/3287d2cc4cdfc907f18089078216a104c644a2d2))
* drop SGML declaration parsing ([4aaf2d9](https://github.com/rubensworks/saxes/commit/4aaf2d94ac4c073b0fd79d83469c08d29de5f231))
* drop the ``parser`` function, rename SAXParser ([0878a6c](https://github.com/rubensworks/saxes/commit/0878a6cc395e79f255064bf9d4b572519029f8fb))
* drop trim ([c03c7d0](https://github.com/rubensworks/saxes/commit/c03c7d00cdd93a7c25ecc1e978f88a52e6039b30))
* pass the actual tag to onclosetag ([7020e64](https://github.com/rubensworks/saxes/commit/7020e6408fabe417c50e04c3fd826e198641ba8a))
* provide default no-op implementation for events ([a94687f](https://github.com/rubensworks/saxes/commit/a94687fb23f90f1072d1b9b0c6f68e00d5ddd0f6))
* remove the API based on Stream ([ebb659a](https://github.com/rubensworks/saxes/commit/ebb659aa4b9ac153b7f1e96f8d3e610f9e485957))
* simplify namespace processing ([2d4ce0f](https://github.com/rubensworks/saxes/commit/2d4ce0f2cace5c4e38fa1823e7400afc319c1551))


### Features

* add forceXMLVersion ([1eedbf8](https://github.com/rubensworks/saxes/commit/1eedbf872b6565543b0e99f554d803874be7456f))
* add makeError method ([50fa39a](https://github.com/rubensworks/saxes/commit/50fa39a70be2fc1e774f36d9914bac3dc0b9c231))
* add support for parsing fragments ([1ff2d6a](https://github.com/rubensworks/saxes/commit/1ff2d6a762b4ac0dd0f13bce9e9b59bc008c74bf))
* add the `resolvePrefix` option ([90301fb](https://github.com/rubensworks/saxes/commit/90301fbeff5a41fb55a07701dfdc2e7cf23815f3))
* add xmldecl event ([a2e677f](https://github.com/rubensworks/saxes/commit/a2e677f01e0e2f0e7dde74659578c104a479d699))
* drop the resume() method; and have onerror() throw ([ac601e5](https://github.com/rubensworks/saxes/commit/ac601e57c5866fd7dd8b4a8d455e575eaf5d404b))
* formal method for setting event listeners ([f346150](https://github.com/rubensworks/saxes/commit/f346150fe29a39c19cb4bd310553bab039348a34))
* handle XML declarations ([5258939](https://github.com/rubensworks/saxes/commit/5258939be1c2ba9a267273d6efb8e143971baa7c))
* process the xmlns attribute the customary way ([2c9672a](https://github.com/rubensworks/saxes/commit/2c9672a514ddfa78f364ab60f3c56ed54646cac3))
* reinstating the attribute events ([7c80f7b](https://github.com/rubensworks/saxes/commit/7c80f7b895516c5380bcd0229f77f2679eb80a4a))
* revamped error messages ([cf9c589](https://github.com/rubensworks/saxes/commit/cf9c5898570aa55bf2c35af579d5f28a8d02540a))
* saxes handles chunks that "break" unicode ([1272448](https://github.com/rubensworks/saxes/commit/1272448eccb2117342017547a7597448f50f79f0))
* saxes is now implemented in TS ([664ba69](https://github.com/rubensworks/saxes/commit/664ba694ded1d24c74332d6639ea779aa08e4506))
* stronger check on bad cdata closure ([d416760](https://github.com/rubensworks/saxes/commit/d416760b4ac2116da38ac9baf295c1ba342f87fe))
* support for XML 1.1 ([36704fb](https://github.com/rubensworks/saxes/commit/36704fb4cb8d3042b262ca992f5df3ef7356ac64))
* the flush method returns its parser ([68c2020](https://github.com/rubensworks/saxes/commit/68c202079cc7b5672251a832618d1bfe4f7dc364))


### Performance Improvements

* add emitNodes to skip checking text buffer more than needed ([9d5e357](https://github.com/rubensworks/saxes/commit/9d5e357a210e88381bc97b5d73389b3835eeffed))
* add topNS for faster namespace processing ([1a33a57](https://github.com/rubensworks/saxes/commit/1a33a57d579290a9e53662019c1d94287100be89))
* capture names in the ``name`` field ([c7dffd5](https://github.com/rubensworks/saxes/commit/c7dffd5e46dee9ea3279081daffc7cbc073241d6))
* check the most common case first ([40a34d5](https://github.com/rubensworks/saxes/commit/40a34d559b5ab7fb2bc15f3a727a8bb730b38adb))
* concatenate openWakaBang just once ([07345bf](https://github.com/rubensworks/saxes/commit/07345bfca6fb878bf06c3cfdd01afed1f4e47ea5))
* don't check twice if this.textNode is set ([00536cc](https://github.com/rubensworks/saxes/commit/00536cc64f1c59f6c7cf247024718a7c2401436b))
* don't depend on limit to know when we hit the end of buffer ([ad4ab53](https://github.com/rubensworks/saxes/commit/ad4ab53da5ddc9b99eee29c279f77f32cea8d3d0))
* don't increment a column number ([490fc24](https://github.com/rubensworks/saxes/commit/490fc24be21a0e925f1a8133cfbb7bd31711ed5d))
* don't repeatedly read this.i in the getCode methods ([d3f196c](https://github.com/rubensworks/saxes/commit/d3f196cedbe4291539a2ad126fca31ff3bdcd9db))
* drop the originalNL flag in favor of a NL_LIKE fake character ([f690725](https://github.com/rubensworks/saxes/commit/f69072520cae496e03483ac299158c99bc099809))
* dump isNaN; it is very costly ([7d97e1a](https://github.com/rubensworks/saxes/commit/7d97e1a565c3d106f7070ae821dc3dc169448837))
* eliminate extra buffers ([3412fcb](https://github.com/rubensworks/saxes/commit/3412fcbd5b11cdd04c1b6eee68b4dc9a900ddea4))
* improve performance of text handling ([9c13099](https://github.com/rubensworks/saxes/commit/9c13099011df6926aed81e964a217d0d763a7966))
* improve some more the speed of ]]> detection ([a0216cd](https://github.com/rubensworks/saxes/commit/a0216cdc5ce4c6255c6fe6c47ce7b1ceb8a1525f))
* improve text node checking speed ([f270e8b](https://github.com/rubensworks/saxes/commit/f270e8b1b8894acfd130c837e71914e0c5e85994))
* improve the check for ]]> in character data ([21df9b5](https://github.com/rubensworks/saxes/commit/21df9b504dd3222ee03287f1be52d70f754ae7d3))
* inline closeText ([07a3b51](https://github.com/rubensworks/saxes/commit/07a3b5199f9cd4b7bc10339a224d12afb78e7a1e))
* introduce a specialized version of captureWhile ([04855d6](https://github.com/rubensworks/saxes/commit/04855d6eb519fa2cd4edf03f8f5a475d40ed047a))
* introduce captureTo and captureToChar ([76eb95a](https://github.com/rubensworks/saxes/commit/76eb95a405678efba0816487415693a269828c55))
* make the most common path of getCode functions the shortest ([4d66bbb](https://github.com/rubensworks/saxes/commit/4d66bbb0b2d1f8e50a6675ec3ba9ea61d4a9a2e2))
* minimine concatenation by adding the capability to unget codes ([27fa8b9](https://github.com/rubensworks/saxes/commit/27fa8b9e91ef42ca51c347fee1d3f546d33b92d3))
* minor optimizations ([c7e36bf](https://github.com/rubensworks/saxes/commit/c7e36bfd89634a9c4ffe1ad44b14fa410561f55c))
* move more common/valid cases first ([a65586e](https://github.com/rubensworks/saxes/commit/a65586ea29f1f8382726ad2da9f43591ffddfc6f))
* reduce the frequency at which we clear attribValue ([1570615](https://github.com/rubensworks/saxes/commit/1570615c63bd6e46d5ffde221c277c71ebb54f39))
* reduce the number of calls to closeText ([3e68df5](https://github.com/rubensworks/saxes/commit/3e68df53078f8a0350ceb998df36e1fec1ef1f39))
* remove an unnecessary variable ([ac03a1c](https://github.com/rubensworks/saxes/commit/ac03a1cb6a4a180f7c8cc3ad7675dd41a9532393))
* remove handler check ([fbe35ff](https://github.com/rubensworks/saxes/commit/fbe35ffcc5e9e6463bf3e65ed5822e2c275cdcd4))
* remove more extra buffers ([b5ee774](https://github.com/rubensworks/saxes/commit/b5ee7747a8baaac7c3adbe8341612448903347be))
* remove skipWhitespace ([c8b7ae2](https://github.com/rubensworks/saxes/commit/c8b7ae2d792bc8145db4ce4fa23fe4c712f440f3))
* remove some redundant buffer resets ([5ded326](https://github.com/rubensworks/saxes/commit/5ded326157d9377e564068a265b647c4fea625ff))
* simplify captureWhile ([bb2085c](https://github.com/rubensworks/saxes/commit/bb2085ccfd1c86aae164fc7e0bc810bdbeba848f))
* simplify the skip functions ([c7b8c3b](https://github.com/rubensworks/saxes/commit/c7b8c3b92e341b94fc0f2d0b399a3bfd5ec6a2e7))
* split sText into two specialized loops ([732325e](https://github.com/rubensworks/saxes/commit/732325ee4dc03cac24ed76845f5e7fc0bcd07afa))
* the c field has been unused for a while: remove it ([9ca0246](https://github.com/rubensworks/saxes/commit/9ca0246c1d850bffc3a85065d1f9981c0eb9e8e1))
* use -1 to mean EOC (end-of-chunk) ([55c0b1b](https://github.com/rubensworks/saxes/commit/55c0b1b24a27a70be3b3f4b87949fee4b74425bd))
* use charCodeAt and handle surrogates ourselves ([b8ec232](https://github.com/rubensworks/saxes/commit/b8ec23222488b4eefbdf5f09d0ee0b04513c5091))
* use isCharAndNotRestricted rather than call two functions ([f0b67a4](https://github.com/rubensworks/saxes/commit/f0b67a4a91173931236f95a7c853f178bd37c74b))
* use slice rather than substring ([c1fed89](https://github.com/rubensworks/saxes/commit/c1fed89c2dd80cafe229aab67b9d498e151d8406))
* use specialized code for sAttribValueQuoted ([6c484f3](https://github.com/rubensworks/saxes/commit/6c484f35ad6c8f0052010c5ad12340187437775f))
* use strings for the general states ([3869908](https://github.com/rubensworks/saxes/commit/38699083fa223f4f35331f05a3686d2f81e1352d))


### BREAKING CHANGES

* we don't support node 10.
* The individually named event handlers no longer exist. You now
must use the methods `on` and `off` to set handlers. Upcoming features require
that saxes know when handlers are added and removed, and it may be necessary in
the future to qualify how to add or remove a handler. Getters/setters are too
restrictives so we bite the bullet now and move to actual methods.
* The fix to column number reporting changes the meaning of the
``column`` field. If you need the old behavior of ``column`` you can use the new
``columnIndex`` field which behaves like the old ``column`` and may be useful in
some contexts. Ultimately you should decide whether your application needs to
know column numbers by Unicode character count or by JavaScript index. (And you
need to know the difference between the two. You can see [this
page](https://mathiasbynens.be/notes/javascript-unicode) for a detailed
discussion of the Unicode problem in JavaScript. Note that the numbers put in
the error messages that ``fail`` produce are still based on the ``column`` field
and thus use the new meaning of ``column``. If you want error message that use
``columnIndex`` you may override the ``fail`` method.
* previous versions of saxes did not consistently convert end of
line characters to NL (0xA) in the data reported by event handlers. This has
been fixed. If your code relied on the old (incorrect) behavior then you'll have
to update it.
* previous versions of saxes would parse files with an XML
declaration set to 1.1 as 1.0 documents. The support for 1.1 entails that if a
document has an XML declaration that specifies version 1.1 it is parsed as a 1.1
document.
* when ``fileName`` is undefined in the parser options saxes does
not show a file name in error messages. Previously it was showing the name
``undefined``. To get the previous behavior, in all cases where you'd leave
``fileName`` undefined, you must set it to the string ``"undefined"`` instead.
* In previous versions the attribute `xmlns` (as in `<foo xmlns="some-uri">` would
be reported as having the prefix `"xmlns"` and the local name `""`.  This
behavior was inherited from sax. There was some logic to it, but this behavior
was surprising to users of the library. The principle of least surprise favors
eliminating that surprising behavior in favor of something less surprising.

This commit makes it so that `xmlns` is not reported as having a prefix of `""`
and a local name of `"xmlns"`. This accords with how people interpret attribute
names like `foo`, `bar`, `moo` which all have no prefix and a local name.

Code that deals with namespace bindings or cares about `xmlns` probably needs to
be changed.
* Sax was only passing the tag name. We pass the whole object.
* * The ``ns`` field is no longer using the prototype trick that sax used. The
  ``ns`` field of a tag contains only those namespaces that the tag declares.

* We no longer have ``opennamespace`` and ``closenamespace`` events. The
  information they provide can be obtained by examining the tags passed to tag
  events.
* ``attribute`` is not a particularly useful event for parsing XML. The only thing
it adds over looking at attributes on tag objects is that you get the order of
the attributes from the source, but attribute order in XML is irrelevant.
* The opencdata and closecdata events became redundant once we removed the buffer
size limitations. So we remove these events.
* The ``parser`` function is removed. Just create a new instance with
``new``.

``SAXParser`` is now ``SaxesParser.`` So ``new
require("saxes").SaxesParser(...)``.
* The API based on Stream is gone. There were multiple issues with it. It was
Node-specific. It used an ancient Node API (the so-called "classic
streams"). Its behavior was idiosyncratic.
* Sax had no default error handler but if you wanted to continue calling
``write()`` after an error you had to call ``resume()``. We do away with
``resume()`` and instead install a default ``onerror`` which throws. Replace
with a no-op handler if you want to continue after errors.
* The "processinginstruction" now produces a "target" field instead of a "name"
field. The nomenclature "target" is the one used in the XML literature.
* By default parsers now have a default no-op implementation for each
event it supports. This would break code that determines whether a
custom handler was added by checking whether there's any handler at
all. This removes the necessity for the parser implementation to check
whether there is a handler before calling it.

In the process of making this change, we've removed support for the
``on...`` properties on streams objects. Their existence was not
warranted by any standard API provided by Node. (``EventEmitter`` does
not have ``on...`` properties for events it supports, nor does
``Stream``.) Their existence was also undocumented. And their
functioning was awkward. For instance, with sax, this:

```
const s = sax.createStream();
const handler = () => console.log("moo");
s.on("cdata", handler);
console.log(s.oncdata === handler);
```

would print ``false``. If you examine ``s.oncdata`` you see it is glue
code instead of the handler assigned. This is just bizarre, so we
removed it.
* SGML declaration is not supported by XML. This is an XML parser. So we
remove support for SGML declarations. They now cause errors.
* We removed support for the code that checked buffer sizes and would
raise errors if a buffer was close to an arbitrary limit or emitted
multiple ``text`` or ``cdata`` events in order avoid passing strings
greater than an arbitrary size. So ``MAX_BUFFER_LENGTH`` is gone.

The feature always seemed a bit awkward. Client code could limit the
size of buffers to 1024K, for instance, and not get a ``text`` event
with a text payload greater than 1024K... so far so good but if the
same document contained a comment with more than 1024K that would
result in an error. Hmm.... why? The distinction seems entirely
arbitrary.

The upshot is that client code needs to be ready to handle strings of
any length supported by the platform.

If there's a clear need to reintroduce it, we'll reassess.
* It is no longer possible to load the library as-is through a
``script`` element. It needs building.

The library now assumes a modern runtime. It no longer contains any
code to polyfill what's missing. It is up to developers using this
code to deal with polyfills as needed.
* We drop the ``trim`` option. It is up to client code to trip text if
it needs it.
* We no longer support the ``normalize`` option. It is up to client code
to perform whatever normalization it wants.
* The ``lowercase`` option makes no sense for XML. It is removed.
* Remove support for strictEntities. Entities are now always strict, as
required by the XML specification.
* The API no longer takes a ``strict`` argument anywhere. This also
effectively removes support for HTML processing, or allow processing
without errors anything which is less than full XML. It also removes
special processing of ``script`` elements.



# [6.0.0](https://github.com/lddubeau/saxes/compare/v6.0.0-rc.1...v6.0.0) (2021-11-07)



# [6.0.0-rc.1](https://github.com/lddubeau/saxes/compare/v5.0.1...v6.0.0-rc.1) (2021-11-07)


### Bug Fixes

* fixing linting errors for eslint 8 ([cd4b5c9](https://github.com/lddubeau/saxes/commit/cd4b5c9ddf166d426ece77349bbde7538fb0aaa4))
* we don't support node 10 anymore ([f2aa1a8](https://github.com/lddubeau/saxes/commit/f2aa1a8e2b379f102010b9c552490f385f7854af))


### BREAKING CHANGES

* we don't support node 10.



<a name="5.0.1"></a>
## [5.0.1](https://github.com/lddubeau/saxes/compare/v5.0.0...v5.0.1) (2020-04-10)


### Bug Fixes

* fix corrupted attribute values when there is no text handler ([e135f11](https://github.com/lddubeau/saxes/commit/e135f11)), closes [#38](https://github.com/lddubeau/saxes/issues/38)



<a name="5.0.0"></a>
# [5.0.0](https://github.com/lddubeau/saxes/compare/v5.0.0-rc.2...v5.0.0) (2020-02-28)



<a name="5.0.0-rc.2"></a>
# [5.0.0-rc.2](https://github.com/lddubeau/saxes/compare/v5.0.0-rc.1...v5.0.0-rc.2) (2020-02-12)



<a name="5.0.0-rc.1"></a>
# [5.0.0-rc.1](https://github.com/lddubeau/saxes/compare/v4.0.2...v5.0.0-rc.1) (2020-02-12)


### Bug Fixes

* disallow BOM characters at the beginning of subsequent chunks ([66d07b6](https://github.com/lddubeau/saxes/commit/66d07b6))
* fix some typing mistakes ([f2a1d5e](https://github.com/lddubeau/saxes/commit/f2a1d5e))
* handle column computation over characters in the astral plane ([cefc8f7](https://github.com/lddubeau/saxes/commit/cefc8f7))


### Features

* add makeError method ([50fa39a](https://github.com/lddubeau/saxes/commit/50fa39a))
* add xmldecl event ([a2e677f](https://github.com/lddubeau/saxes/commit/a2e677f))
* formal method for setting event listeners ([f346150](https://github.com/lddubeau/saxes/commit/f346150))
* reinstating the attribute events ([7c80f7b](https://github.com/lddubeau/saxes/commit/7c80f7b))
* saxes is now implemented in TS ([664ba69](https://github.com/lddubeau/saxes/commit/664ba69))


### Performance Improvements

* add topNS for faster namespace processing ([1a33a57](https://github.com/lddubeau/saxes/commit/1a33a57))


### BREAKING CHANGES

* The individually named event handlers no longer exist. You now
must use the methods `on` and `off` to set handlers. Upcoming features require
that saxes know when handlers are added and removed, and it may be necessary in
the future to qualify how to add or remove a handler. Getters/setters are too
restrictives so we bite the bullet now and move to actual methods.
* The fix to column number reporting changes the meaning of the
``column`` field. If you need the old behavior of ``column`` you can use the new
``columnIndex`` field which behaves like the old ``column`` and may be useful in
some contexts. Ultimately you should decide whether your application needs to
know column numbers by Unicode character count or by JavaScript index. (And you
need to know the difference between the two. You can see [this
page](https://mathiasbynens.be/notes/javascript-unicode) for a detailed
discussion of the Unicode problem in JavaScript. Note that the numbers put in
the error messages that ``fail`` produce are still based on the ``column`` field
and thus use the new meaning of ``column``. If you want error message that use
``columnIndex`` you may override the ``fail`` method.



<a name="4.0.2"></a>
## [4.0.2](https://github.com/lddubeau/saxes/compare/v4.0.0-rc.4...v4.0.2) (2019-10-14)



<a name="4.0.1"></a>
## [4.0.1](https://github.com/lddubeau/saxes/compare/v4.0.0...v4.0.1) (2019-10-14)



<a name="4.0.0"></a>
# [4.0.0](https://github.com/lddubeau/saxes/compare/v4.0.0-rc.4...v4.0.0) (2019-10-14)



<a name="4.0.0-rc.4"></a>
# [4.0.0-rc.4](https://github.com/lddubeau/saxes/compare/v4.0.0-rc.2...v4.0.0-rc.4) (2019-10-11)


### Bug Fixes

* fix a bug in EOL handling ([bed38a8](https://github.com/lddubeau/saxes/commit/bed38a8))
* implement attribute normalization ([be51114](https://github.com/lddubeau/saxes/commit/be51114)), closes [#24](https://github.com/lddubeau/saxes/issues/24)


### Performance Improvements

* inline closeText ([07a3b51](https://github.com/lddubeau/saxes/commit/07a3b51))



<a name="4.0.0-rc.3"></a>
# [4.0.0-rc.3](https://github.com/lddubeau/saxes/compare/v4.0.0-rc.2...v4.0.0-rc.3) (2019-10-11)


### Bug Fixes

* fix a bug in EOL handling ([03b1567](https://github.com/lddubeau/saxes/commit/03b1567))
* implement attribute normalization ([6580844](https://github.com/lddubeau/saxes/commit/6580844)), closes [#24](https://github.com/lddubeau/saxes/issues/24)


### Performance Improvements

* inline closeText ([1c8df1a](https://github.com/lddubeau/saxes/commit/1c8df1a))



<a name="4.0.0-rc.2"></a>
# [4.0.0-rc.2](https://github.com/lddubeau/saxes/compare/v4.0.0-rc.1...v4.0.0-rc.2) (2019-10-04)


### Performance Improvements

* drop the originalNL flag in favor of a NL_LIKE fake character ([f690725](https://github.com/lddubeau/saxes/commit/f690725))
* dump isNaN; it is very costly ([7d97e1a](https://github.com/lddubeau/saxes/commit/7d97e1a))
* eliminate extra buffers ([3412fcb](https://github.com/lddubeau/saxes/commit/3412fcb))
* reduce the number of calls to closeText ([3e68df5](https://github.com/lddubeau/saxes/commit/3e68df5))
* remove more extra buffers ([b5ee774](https://github.com/lddubeau/saxes/commit/b5ee774))
* use -1 to mean EOC (end-of-chunk) ([55c0b1b](https://github.com/lddubeau/saxes/commit/55c0b1b))



<a name="4.0.0-rc.1"></a>
# [4.0.0-rc.1](https://github.com/lddubeau/saxes/compare/v3.1.11...v4.0.0-rc.1) (2019-10-02)


### Bug Fixes

* don't serialize the fileName as undefined: when not present ([4ff2365](https://github.com/lddubeau/saxes/commit/4ff2365))
* fix bug with initial eol characters ([7b3db75](https://github.com/lddubeau/saxes/commit/7b3db75))
* handling of end of line characters ([f13247a](https://github.com/lddubeau/saxes/commit/f13247a))


### Features

* add forceXMLVersion ([1eedbf8](https://github.com/lddubeau/saxes/commit/1eedbf8))
* saxes handles chunks that "break" unicode ([1272448](https://github.com/lddubeau/saxes/commit/1272448))
* support for XML 1.1 ([36704fb](https://github.com/lddubeau/saxes/commit/36704fb))


### Performance Improvements

* don't depend on limit to know when we hit the end of buffer ([ad4ab53](https://github.com/lddubeau/saxes/commit/ad4ab53))
* don't increment a column number ([490fc24](https://github.com/lddubeau/saxes/commit/490fc24))
* don't repeatedly read this.i in the getCode methods ([d3f196c](https://github.com/lddubeau/saxes/commit/d3f196c))
* improve performance of text handling ([9c13099](https://github.com/lddubeau/saxes/commit/9c13099))
* make the most common path of getCode functions the shortest ([4d66bbb](https://github.com/lddubeau/saxes/commit/4d66bbb))
* minimine concatenation by adding the capability to unget codes ([27fa8b9](https://github.com/lddubeau/saxes/commit/27fa8b9))
* use isCharAndNotRestricted rather than call two functions ([f0b67a4](https://github.com/lddubeau/saxes/commit/f0b67a4))
* use slice rather than substring ([c1fed89](https://github.com/lddubeau/saxes/commit/c1fed89))


### BREAKING CHANGES

* previous versions of saxes did not consistently convert end of
line characters to NL (0xA) in the data reported by event handlers. This has
been fixed. If your code relied on the old (incorrect) behavior then you'll have
to update it.
* previous versions of saxes would parse files with an XML
declaration set to 1.1 as 1.0 documents. The support for 1.1 entails that if a
document has an XML declaration that specifies version 1.1 it is parsed as a 1.1
document.
* when ``fileName`` is undefined in the parser options saxes does
not show a file name in error messages. Previously it was showing the name
``undefined``. To get the previous behavior, in all cases where you'd leave
``fileName`` undefined, you must set it to the string ``"undefined"`` instead.



<a name="3.1.11"></a>
## [3.1.11](https://github.com/lddubeau/saxes/compare/v3.1.10...v3.1.11) (2019-06-25)


### Bug Fixes

* pay attention to comments and processing instructions in DTDs ([52ffd90](https://github.com/lddubeau/saxes/commit/52ffd90)), closes [#19](https://github.com/lddubeau/saxes/issues/19)


### Performance Improvements

* check the most common case first ([40a34d5](https://github.com/lddubeau/saxes/commit/40a34d5))
* improve some more the speed of ]]> detection ([a0216cd](https://github.com/lddubeau/saxes/commit/a0216cd))
* move more common/valid cases first ([a65586e](https://github.com/lddubeau/saxes/commit/a65586e))
* split sText into two specialized loops ([732325e](https://github.com/lddubeau/saxes/commit/732325e))
* use specialized code for sAttribValueQuoted ([6c484f3](https://github.com/lddubeau/saxes/commit/6c484f3))



<a name="3.1.10"></a>
## [3.1.10](https://github.com/lddubeau/saxes/compare/v3.1.9...v3.1.10) (2019-06-11)


### Performance Improvements

* improve the check for ]]> in character data ([21df9b5](https://github.com/lddubeau/saxes/commit/21df9b5))



<a name="3.1.9"></a>
## [3.1.9](https://github.com/lddubeau/saxes/compare/v3.1.7...v3.1.9) (2019-02-25)


### Bug Fixes

* move eslint to devDependencies ([d747538](https://github.com/lddubeau/saxes/commit/d747538))



<a name="3.1.8"></a>
## [3.1.8](https://github.com/lddubeau/saxes/compare/v3.1.7...v3.1.8) (2019-02-25)



<a name="3.1.7"></a>
## [3.1.7](https://github.com/lddubeau/saxes/compare/v3.1.6...v3.1.7) (2019-02-22)


### Bug Fixes

* npm audit warning ([a6c9ba8](https://github.com/lddubeau/saxes/commit/a6c9ba8))
* **typings:** "selfClosing" => "isSelfClosing" ([d96a2bd](https://github.com/lddubeau/saxes/commit/d96a2bd))



<a name="3.1.6"></a>
## [3.1.6](https://github.com/lddubeau/saxes/compare/v3.1.5...v3.1.6) (2019-01-17)


### Bug Fixes

* detect unclosed tags in fragments ([5642f36](https://github.com/lddubeau/saxes/commit/5642f36))



<a name="3.1.5"></a>
## [3.1.5](https://github.com/lddubeau/saxes/compare/v3.1.4...v3.1.5) (2019-01-08)


### Bug Fixes

* generate an error on prefix with empty local name ([89a3b86](https://github.com/lddubeau/saxes/commit/89a3b86)), closes [#5](https://github.com/lddubeau/saxes/issues/5)



<a name="3.1.4"></a>
## [3.1.4](https://github.com/lddubeau/saxes/compare/v3.1.3...v3.1.4) (2018-12-03)


### Bug Fixes

* add fragment and additionalNamespaces to SaxesOption typing ([02d8275](https://github.com/lddubeau/saxes/commit/02d8275))



<a name="3.1.3"></a>
## [3.1.3](https://github.com/lddubeau/saxes/compare/v3.1.2...v3.1.3) (2018-10-01)


### Bug Fixes

* use the latest xmlchars ([b30a714](https://github.com/lddubeau/saxes/commit/b30a714))


### Performance Improvements

* don't check twice if this.textNode is set ([00536cc](https://github.com/lddubeau/saxes/commit/00536cc))
* reduce the frequency at which we clear attribValue ([1570615](https://github.com/lddubeau/saxes/commit/1570615))



<a name="3.1.2"></a>
## [3.1.2](https://github.com/lddubeau/saxes/compare/v3.1.1...v3.1.2) (2018-08-31)


### Bug Fixes

* CDATA end in attributes must not cause an error ([a7495ac](https://github.com/lddubeau/saxes/commit/a7495ac))
* normalize \r\n and \r followed by something else to \n ([d7b1abe](https://github.com/lddubeau/saxes/commit/d7b1abe)), closes [#2](https://github.com/lddubeau/saxes/issues/2)



<a name="3.1.1"></a>
## [3.1.1](https://github.com/lddubeau/saxes/compare/v3.1.0...v3.1.1) (2018-08-29)


### Bug Fixes

* resolve is now part of the public API ([bb4bed5](https://github.com/lddubeau/saxes/commit/bb4bed5))



<a name="3.1.0"></a>
# [3.1.0](https://github.com/lddubeau/saxes/compare/v3.0.0...v3.1.0) (2018-08-28)


### Bug Fixes

* correct typo ([97bc5da](https://github.com/lddubeau/saxes/commit/97bc5da))


### Performance Improvements

* add emitNodes to skip checking text buffer more than needed ([9d5e357](https://github.com/lddubeau/saxes/commit/9d5e357))
* capture names in the ``name`` field ([c7dffd5](https://github.com/lddubeau/saxes/commit/c7dffd5))
* introduce a specialized version of captureWhile ([04855d6](https://github.com/lddubeau/saxes/commit/04855d6))
* introduce captureTo and captureToChar ([76eb95a](https://github.com/lddubeau/saxes/commit/76eb95a))
* remove skipWhitespace ([c8b7ae2](https://github.com/lddubeau/saxes/commit/c8b7ae2))
* remove some redundant buffer resets ([5ded326](https://github.com/lddubeau/saxes/commit/5ded326))
* use charCodeAt and handle surrogates ourselves ([b8ec232](https://github.com/lddubeau/saxes/commit/b8ec232))



<a name="3.0.0"></a>
# [3.0.0](https://github.com/lddubeau/saxes/compare/v2.2.1...v3.0.0) (2018-08-21)


### Features

* process the xmlns attribute the customary way ([2c9672a](https://github.com/lddubeau/saxes/commit/2c9672a))


### BREAKING CHANGES

* In previous versions the attribute `xmlns` (as in `<foo xmlns="some-uri">` would
be reported as having the prefix `"xmlns"` and the local name `""`.  This
behavior was inherited from sax. There was some logic to it, but this behavior
was surprising to users of the library. The principle of least surprise favors
eliminating that surprising behavior in favor of something less surprising.

This commit makes it so that `xmlns` is not reported as having a prefix of `""`
and a local name of `"xmlns"`. This accords with how people interpret attribute
names like `foo`, `bar`, `moo` which all have no prefix and a local name.

Code that deals with namespace bindings or cares about `xmlns` probably needs to
be changed.



<a name="2.2.1"></a>
## [2.2.1](https://github.com/lddubeau/saxes/compare/v2.2.0...v2.2.1) (2018-08-20)


### Bug Fixes

* use `isNameChar` for later chars in PI target ([83d2b61](https://github.com/lddubeau/saxes/commit/83d2b61))



<a name="2.2.0"></a>
# [2.2.0](https://github.com/lddubeau/saxes/compare/v2.1.0...v2.2.0) (2018-08-20)


### Features

* add the `resolvePrefix` option ([90301fb](https://github.com/lddubeau/saxes/commit/90301fb))



<a name="2.1.0"></a>
# [2.1.0](https://github.com/lddubeau/saxes/compare/v2.0.0...v2.1.0) (2018-08-20)


### Features

* add support for parsing fragments ([1ff2d6a](https://github.com/lddubeau/saxes/commit/1ff2d6a))
* stronger check on bad cdata closure ([d416760](https://github.com/lddubeau/saxes/commit/d416760))


### Performance Improvements

* concatenate openWakaBang just once ([07345bf](https://github.com/lddubeau/saxes/commit/07345bf))
* improve text node checking speed ([f270e8b](https://github.com/lddubeau/saxes/commit/f270e8b))
* minor optimizations ([c7e36bf](https://github.com/lddubeau/saxes/commit/c7e36bf))
* remove an unnecessary variable ([ac03a1c](https://github.com/lddubeau/saxes/commit/ac03a1c))
* remove handler check ([fbe35ff](https://github.com/lddubeau/saxes/commit/fbe35ff))
* simplify captureWhile ([bb2085c](https://github.com/lddubeau/saxes/commit/bb2085c))
* simplify the skip functions ([c7b8c3b](https://github.com/lddubeau/saxes/commit/c7b8c3b))
* the c field has been unused for a while: remove it ([9ca0246](https://github.com/lddubeau/saxes/commit/9ca0246))
* use strings for the general states ([3869908](https://github.com/lddubeau/saxes/commit/3869908))



<a name="2.0.0"></a>
# [2.0.0](https://github.com/lddubeau/saxes/compare/v1.2.4...v2.0.0) (2018-07-23)


### Bug Fixes

* "X" is not a valid hex prefix for char references ([465038b](https://github.com/lddubeau/saxes/commit/465038b))
* add namespace checks ([9f94c4b](https://github.com/lddubeau/saxes/commit/9f94c4b))
* always run in strict mode ([ed8b0b1](https://github.com/lddubeau/saxes/commit/ed8b0b1))
* check that the characters we read are valid char data ([7611a85](https://github.com/lddubeau/saxes/commit/7611a85))
* disallow spaces after open waka ([da7f76d](https://github.com/lddubeau/saxes/commit/da7f76d))
* drop the lowercase option ([987d4bf](https://github.com/lddubeau/saxes/commit/987d4bf))
* emit CDATA on empty CDATA section too ([95d192f](https://github.com/lddubeau/saxes/commit/95d192f))
* emit empty comment ([b3db392](https://github.com/lddubeau/saxes/commit/b3db392))
* entities are always strict ([0f6a30e](https://github.com/lddubeau/saxes/commit/0f6a30e))
* fail on colon at start of QName ([507addd](https://github.com/lddubeau/saxes/commit/507addd))
* harmonize error messages and initialize flags ([9a20cad](https://github.com/lddubeau/saxes/commit/9a20cad))
* just one error for text before the root, and text after ([101ea50](https://github.com/lddubeau/saxes/commit/101ea50))
* more namespace checks ([a1add21](https://github.com/lddubeau/saxes/commit/a1add21))
* move namespace checks to their proper place ([4a1c99f](https://github.com/lddubeau/saxes/commit/4a1c99f))
* only accept uppercase CDATA to mark the start of CDATA ([e86534d](https://github.com/lddubeau/saxes/commit/e86534d))
* prevent colons in pi and entity names when xmlns is true ([4327eec](https://github.com/lddubeau/saxes/commit/4327eec))
* prevent empty entities ([04e1593](https://github.com/lddubeau/saxes/commit/04e1593))
* raise an error if the document does not have a root ([f2de520](https://github.com/lddubeau/saxes/commit/f2de520))
* raise an error on ]]> in character data ([2964381](https://github.com/lddubeau/saxes/commit/2964381))
* raise an error on < in attribute values ([4fd67a1](https://github.com/lddubeau/saxes/commit/4fd67a1))
* raise an error on multiple root elements ([45047ae](https://github.com/lddubeau/saxes/commit/45047ae))
* raise error on CDATA before or after root ([604241f](https://github.com/lddubeau/saxes/commit/604241f))
* raise error on character reference outside CHAR production ([30fb540](https://github.com/lddubeau/saxes/commit/30fb540))
* remove broken or pointless examples ([1a5b642](https://github.com/lddubeau/saxes/commit/1a5b642))
* report an error on duplicate attributes ([ee4e340](https://github.com/lddubeau/saxes/commit/ee4e340))
* report an error on whitespace at the start of end tag ([c13b122](https://github.com/lddubeau/saxes/commit/c13b122))
* report processing instructions that do not have a target ([c007e39](https://github.com/lddubeau/saxes/commit/c007e39))
* treat ?? in processing instructions correctly ([bc1e1d4](https://github.com/lddubeau/saxes/commit/bc1e1d4))
* trim URIs ([78cc6f3](https://github.com/lddubeau/saxes/commit/78cc6f3))
* use xmlchars for checking names ([2c939fe](https://github.com/lddubeau/saxes/commit/2c939fe))
* verify that character references match the CHAR production ([369afde](https://github.com/lddubeau/saxes/commit/369afde))


### Code Refactoring

* adjust the names used for processing instructions ([3b508e9](https://github.com/lddubeau/saxes/commit/3b508e9))
* convert code to ES6 ([fe81170](https://github.com/lddubeau/saxes/commit/fe81170))
* drop attribute event ([c7c2e80](https://github.com/lddubeau/saxes/commit/c7c2e80))
* drop buffer size checks ([9ce2f7a](https://github.com/lddubeau/saxes/commit/9ce2f7a))
* drop normalize ([9c6d84c](https://github.com/lddubeau/saxes/commit/9c6d84c))
* drop opencdata and on closecdata ([3287d2c](https://github.com/lddubeau/saxes/commit/3287d2c))
* drop SGML declaration parsing ([4aaf2d9](https://github.com/lddubeau/saxes/commit/4aaf2d9))
* drop the ``parser`` function, rename SAXParser ([0878a6c](https://github.com/lddubeau/saxes/commit/0878a6c))
* drop trim ([c03c7d0](https://github.com/lddubeau/saxes/commit/c03c7d0))
* pass the actual tag to onclosetag ([7020e64](https://github.com/lddubeau/saxes/commit/7020e64))
* provide default no-op implementation for events ([a94687f](https://github.com/lddubeau/saxes/commit/a94687f))
* remove the API based on Stream ([ebb659a](https://github.com/lddubeau/saxes/commit/ebb659a))
* simplify namespace processing ([2d4ce0f](https://github.com/lddubeau/saxes/commit/2d4ce0f))


### Features

* drop the resume() method; and have onerror() throw ([ac601e5](https://github.com/lddubeau/saxes/commit/ac601e5))
* handle XML declarations ([5258939](https://github.com/lddubeau/saxes/commit/5258939))
* revamped error messages ([cf9c589](https://github.com/lddubeau/saxes/commit/cf9c589))
* the flush method returns its parser ([68c2020](https://github.com/lddubeau/saxes/commit/68c2020))


### BREAKING CHANGES

* Sax was only passing the tag name. We pass the whole object.
* The API no longer takes a ``strict`` argument anywhere. This also
effectively removes support for HTML processing, or allow processing
without errors anything which is less than full XML. It also removes
special processing of ``script`` elements.
* ``attribute`` is not a particularly useful event for parsing XML. The only thing
it adds over looking at attributes on tag objects is that you get the order of
the attributes from the source, but attribute order in XML is irrelevant.
* The opencdata and closecdata events became redundant once we removed the buffer
size limitations. So we remove these events.
* The ``parser`` function is removed. Just create a new instance with
``new``.

``SAXParser`` is now ``SaxesParser.`` So ``new
require("saxes").SaxesParser(...)``.
* The API based on Stream is gone. There were multiple issues with it. It was
Node-specific. It used an ancient Node API (the so-called "classic
streams"). Its behavior was idiosyncratic.
* Sax had no default error handler but if you wanted to continue calling
``write()`` after an error you had to call ``resume()``. We do away with
``resume()`` and instead install a default ``onerror`` which throws. Replace
with a no-op handler if you want to continue after errors.
* The "processinginstruction" now produces a "target" field instead of a "name"
field. The nomenclature "target" is the one used in the XML literature.
* * The ``ns`` field is no longer using the prototype trick that sax used. The
  ``ns`` field of a tag contains only those namespaces that the tag declares.

* We no longer have ``opennamespace`` and ``closenamespace`` events. The
  information they provide can be obtained by examining the tags passed to tag
  events.
* SGML declaration is not supported by XML. This is an XML parser. So we
remove support for SGML declarations. They now cause errors.
* We removed support for the code that checked buffer sizes and would
raise errors if a buffer was close to an arbitrary limit or emitted
multiple ``text`` or ``cdata`` events in order avoid passing strings
greater than an arbitrary size. So ``MAX_BUFFER_LENGTH`` is gone.

The feature always seemed a bit awkward. Client code could limit the
size of buffers to 1024K, for instance, and not get a ``text`` event
with a text payload greater than 1024K... so far so good but if the
same document contained a comment with more than 1024K that would
result in an error. Hmm.... why? The distinction seems entirely
arbitrary.

The upshot is that client code needs to be ready to handle strings of
any length supported by the platform.

If there's a clear need to reintroduce it, we'll reassess.
* It is no longer possible to load the library as-is through a
``script`` element. It needs building.

The library now assumes a modern runtime. It no longer contains any
code to polyfill what's missing. It is up to developers using this
code to deal with polyfills as needed.
* We drop the ``trim`` option. It is up to client code to trip text if
it needs it.
* We no longer support the ``normalize`` option. It is up to client code
to perform whatever normalization it wants.
* The ``lowercase`` option makes no sense for XML. It is removed.
* Remove support for strictEntities. Entities are now always strict, as
required by the XML specification.
* By default parsers now have a default no-op implementation for each
event it supports. This would break code that determines whether a
custom handler was added by checking whether there's any handler at
all. This removes the necessity for the parser implementation to check
whether there is a handler before calling it.

In the process of making this change, we've removed support for the
``on...`` properties on streams objects. Their existence was not
warranted by any standard API provided by Node. (``EventEmitter`` does
not have ``on...`` properties for events it supports, nor does
``Stream``.) Their existence was also undocumented. And their
functioning was awkward. For instance, with sax, this:

```
const s = sax.createStream();
const handler = () => console.log("moo");
s.on("cdata", handler);
console.log(s.oncdata === handler);
```

would print ``false``. If you examine ``s.oncdata`` you see it is glue
code instead of the handler assigned. This is just bizarre, so we
removed it.



