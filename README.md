nonameapp
=========

app
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>CFBundleDevelopmentRegion</key>
	<string>en</string>
	<key>CFBundleDisplayName</key>
	<string>${PRODUCT_NAME}</string>
	<key>CFBundleExecutable</key>
	<string>${EXECUTABLE_NAME}</string>
	<key>CFBundleIconFiles</key>
	<array/>
	<key>CFBundleIdentifier</key>
	<string>com.thickmug.${PRODUCT_NAME:rfc1034identifier}</string>
	<key>CFBundleInfoDictionaryVersion</key>
	<string>6.0</string>
	<key>CFBundleName</key>
	<string>${PRODUCT_NAME}</string>
	<key>CFBundlePackageType</key>
	<string>APPL</string>
	<key>CFBundleShortVersionString</key>
	<string>1.0</string>
	<key>CFBundleSignature</key>
	<string>????</string>
	<key>CFBundleVersion</key>
	<string>1.0</string>
	<key>LSRequiresIPhoneOS</key>
	<true/>
	<key>UIRequiredDeviceCapabilities</key>
	<array>
		<string>armv7</string>
	</array>
	<key>UISupportedInterfaceOrientations</key>
	<array>
		<string>UIInterfaceOrientationPortrait</string>
		<string>UIInterfaceOrientationLandscapeLeft</string>
		<string>UIInterfaceOrientationLandscapeRight</string>
	</array>
	<key>UISupportedInterfaceOrientations~ipad</key>
	<array>
		<string>UIInterfaceOrientationPortrait</string>
		<string>UIInterfaceOrientationPortraitUpsideDown</string>
		<string>UIInterfaceOrientationLandscapeLeft</string>
		<string>UIInterfaceOrientationLandscapeRight</string>
	</array>
</dict>
</plist>
<?xml version="1.0" encoding="UTF-8"?>
<archive type="com.apple.InterfaceBuilder3.CocoaTouch.XIB" version="8.00">
	<data>
		<int key="IBDocument.SystemTarget">1280</int>
		<string key="IBDocument.SystemVersion">10K549</string>
		<string key="IBDocument.InterfaceBuilderVersion">1938</string>
		<string key="IBDocument.AppKitVersion">1038.36</string>
		<string key="IBDocument.HIToolboxVersion">461.00</string>
		<object class="NSMutableDictionary" key="IBDocument.PluginVersions">
			<string key="NS.key.0">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
			<string key="NS.object.0">933</string>
		</object>
		<array key="IBDocument.IntegratedClassDependencies">
			<string>IBUIButton</string>
			<string>IBUIBarButtonItem</string>
			<string>IBUIImageView</string>
			<string>IBUIToolbar</string>
			<string>IBProxyObject</string>
			<string>IBUILabel</string>
			<string>IBUISlider</string>
			<string>IBUIView</string>
		</array>
		<array key="IBDocument.PluginDependencies">
			<string>com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
		</array>
		<object class="NSMutableDictionary" key="IBDocument.Metadata">
			<string key="NS.key.0">PluginDependencyRecalculationVersion</string>
			<integer value="1" key="NS.object.0"/>
		</object>
		<array class="NSMutableArray" key="IBDocument.RootObjects" id="1000">
			<object class="IBProxyObject" id="372490531">
				<string key="IBProxiedObjectIdentifier">IBFilesOwner</string>
				<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
			</object>
			<object class="IBProxyObject" id="843779117">
				<string key="IBProxiedObjectIdentifier">IBFirstResponder</string>
				<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
			</object>
			<object class="IBUIView" id="774585933">
				<reference key="NSNextResponder"/>
				<int key="NSvFlags">274</int>
				<array class="NSMutableArray" key="NSSubviews">
					<object class="IBUIToolbar" id="581521566">
						<reference key="NSNextResponder" ref="774585933"/>
						<int key="NSvFlags">266</int>
						<array class="NSMutableArray" key="NSSubviews">
							<object class="IBUIView" id="549809473">
								<reference key="NSNextResponder" ref="581521566"/>
								<int key="NSvFlags">274</int>
								<string key="NSFrame">{{12, 6}, {296, 33}}</string>
								<reference key="NSSuperview" ref="581521566"/>
								<reference key="NSWindow"/>
								<reference key="NSNextKeyView"/>
								<object class="NSColor" key="IBUIBackgroundColor" id="487574684">
									<int key="NSColorSpace">3</int>
									<bytes key="NSWhite">MCAwAA</bytes>
								</object>
								<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
							</object>
						</array>
						<string key="NSFrame">{{0, 416}, {320, 44}}</string>
						<reference key="NSSuperview" ref="774585933"/>
						<reference key="NSWindow"/>
						<reference key="NSNextKeyView" ref="549809473"/>
						<bool key="IBUIOpaque">NO</bool>
						<bool key="IBUIClearsContextBeforeDrawing">NO</bool>
						<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
						<array class="NSMutableArray" key="IBUIItems">
							<object class="IBUIBarButtonItem" id="13771401">
								<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
								<reference key="IBUICustomView" ref="549809473"/>
								<reference key="IBUIToolbar" ref="581521566"/>
							</object>
						</array>
					</object>
					<object class="IBUIImageView" id="667631667">
						<reference key="NSNextResponder" ref="774585933"/>
						<int key="NSvFlags">268</int>
						<string key="NSFrame">{{15, 208}, {290, 194}}</string>
						<reference key="NSSuperview" ref="774585933"/>
						<reference key="NSWindow"/>
						<reference key="NSNextKeyView" ref="581521566"/>
						<bool key="IBUIUserInteractionEnabled">NO</bool>
						<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
					</object>
					<object class="IBUILabel" id="347708628">
						<reference key="NSNextResponder" ref="774585933"/>
						<int key="NSvFlags">289</int>
						<string key="NSFrame">{{112, 180}, {96, 20}}</string>
						<reference key="NSSuperview" ref="774585933"/>
						<reference key="NSWindow"/>
						<reference key="NSNextKeyView" ref="667631667"/>
						<bool key="IBUIOpaque">NO</bool>
						<bool key="IBUIClipsSubviews">YES</bool>
						<int key="IBUIContentMode">7</int>
						<bool key="IBUIUserInteractionEnabled">NO</bool>
						<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
						<string key="IBUIText">1 of 100</string>
						<object class="NSColor" key="IBUITextColor" id="103932968">
							<int key="NSColorSpace">3</int>
							<bytes key="NSWhite">MQA</bytes>
						</object>
						<nil key="IBUIHighlightedColor"/>
						<object class="NSColor" key="IBUIShadowColor">
							<int key="NSColorSpace">3</int>
							<bytes key="NSWhite">MC42NjY2NjY2NjY3AA</bytes>
						</object>
						<int key="IBUIBaselineAdjustment">1</int>
						<float key="IBUIMinimumFontSize">10</float>
						<int key="IBUITextAlignment">1</int>
						<object class="IBUIFontDescription" key="IBUIFontDescription">
							<int key="type">2</int>
							<double key="pointSize">20</double>
						</object>
						<object class="NSFont" key="IBUIFont">
							<string key="NSName">Helvetica-Bold</string>
							<double key="NSSize">20</double>
							<int key="NSfFlags">16</int>
						</object>
					</object>
					<object class="IBUIView" id="373608001">
						<reference key="NSNextResponder" ref="774585933"/>
						<int key="NSvFlags">289</int>
						<array class="NSMutableArray" key="NSSubviews">
							<object class="IBUIButton" id="1420102">
								<reference key="NSNextResponder" ref="373608001"/>
								<int key="NSvFlags">294</int>
								<string key="NSFrame">{{0, 102}, {135, 37}}</string>
								<reference key="NSSuperview" ref="373608001"/>
								<reference key="NSWindow"/>
								<reference key="NSNextKeyView" ref="572627251"/>
								<bool key="IBUIOpaque">NO</bool>
								<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
								<int key="IBUIContentHorizontalAlignment">0</int>
								<int key="IBUIContentVerticalAlignment">0</int>
								<int key="IBUIButtonType">1</int>
								<string key="IBUINormalTitle">Reload</string>
								<reference key="IBUIHighlightedTitleColor" ref="103932968"/>
								<object class="NSColor" key="IBUINormalTitleColor">
									<int key="NSColorSpace">1</int>
									<bytes key="NSRGB">MC4xOTYwNzg0MzQ2IDAuMzA5ODAzOTMyOSAwLjUyMTU2ODY1NgA</bytes>
								</object>
								<object class="NSColor" key="IBUINormalTitleShadowColor">
									<int key="NSColorSpace">3</int>
									<bytes key="NSWhite">MC41AA</bytes>
								</object>
								<object class="IBUIFontDescription" key="IBUIFontDescription">
									<int key="type">2</int>
									<double key="pointSize">15</double>
								</object>
								<object class="NSFont" key="IBUIFont">
									<string key="NSName">Helvetica-Bold</string>
									<double key="NSSize">15</double>
									<int key="NSfFlags">16</int>
								</object>
							</object>
							<object class="IBUILabel" id="572627251">
								<reference key="NSNextResponder" ref="373608001"/>
								<int key="NSvFlags">291</int>
								<string key="NSFrame">{{150, 102}, {135, 37}}</string>
								<reference key="NSSuperview" ref="373608001"/>
								<reference key="NSWindow"/>
								<reference key="NSNextKeyView" ref="347708628"/>
								<bool key="IBUIOpaque">NO</bool>
								<bool key="IBUIClipsSubviews">YES</bool>
								<int key="IBUIContentMode">7</int>
								<bool key="IBUIUserInteractionEnabled">NO</bool>
								<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
								<string key="IBUIText">reloaded in</string>
								<reference key="IBUITextColor" ref="103932968"/>
								<nil key="IBUIHighlightedColor"/>
								<int key="IBUIBaselineAdjustment">1</int>
								<float key="IBUIMinimumFontSize">10</float>
								<int key="IBUINumberOfLines">2</int>
								<int key="IBUITextAlignment">1</int>
								<object class="IBUIFontDescription" key="IBUIFontDescription" id="439016584">
									<int key="type">1</int>
									<double key="pointSize">14</double>
								</object>
								<object class="NSFont" key="IBUIFont" id="1051881456">
									<string key="NSName">Helvetica</string>
									<double key="NSSize">14</double>
									<int key="NSfFlags">16</int>
								</object>
							</object>
							<object class="IBUISlider" id="262915402">
								<reference key="NSNextResponder" ref="373608001"/>
								<int key="NSvFlags">294</int>
								<string key="NSFrame">{{-2, 22}, {289, 23}}</string>
								<reference key="NSSuperview" ref="373608001"/>
								<reference key="NSWindow"/>
								<reference key="NSNextKeyView" ref="625660746"/>
								<bool key="IBUIOpaque">NO</bool>
								<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
								<int key="IBUIContentHorizontalAlignment">0</int>
								<int key="IBUIContentVerticalAlignment">0</int>
							</object>
							<object class="IBUISlider" id="625660746">
								<reference key="NSNextResponder" ref="373608001"/>
								<int key="NSvFlags">294</int>
								<string key="NSFrame">{{-2, 72}, {289, 23}}</string>
								<reference key="NSSuperview" ref="373608001"/>
								<reference key="NSWindow"/>
								<reference key="NSNextKeyView" ref="188072306"/>
								<bool key="IBUIOpaque">NO</bool>
								<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
								<int key="IBUIContentHorizontalAlignment">0</int>
								<int key="IBUIContentVerticalAlignment">0</int>
							</object>
							<object class="IBUILabel" id="637654008">
								<reference key="NSNextResponder" ref="373608001"/>
								<int key="NSvFlags">292</int>
								<string key="NSFrameSize">{124, 21}</string>
								<reference key="NSSuperview" ref="373608001"/>
								<reference key="NSWindow"/>
								<reference key="NSNextKeyView" ref="141709788"/>
								<bool key="IBUIOpaque">NO</bool>
								<bool key="IBUIClipsSubviews">YES</bool>
								<int key="IBUIContentMode">7</int>
								<bool key="IBUIUserInteractionEnabled">NO</bool>
								<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
								<string key="IBUIText">number of images:</string>
								<reference key="IBUITextColor" ref="103932968"/>
								<nil key="IBUIHighlightedColor"/>
								<int key="IBUIBaselineAdjustment">1</int>
								<float key="IBUIMinimumFontSize">10</float>
								<reference key="IBUIFontDescription" ref="439016584"/>
								<reference key="IBUIFont" ref="1051881456"/>
							</object>
							<object class="IBUILabel" id="141709788">
								<reference key="NSNextResponder" ref="373608001"/>
								<int key="NSvFlags">292</int>
								<string key="NSFrame">{{113, 0}, {37, 21}}</string>
								<reference key="NSSuperview" ref="373608001"/>
								<reference key="NSWindow"/>
								<reference key="NSNextKeyView" ref="262915402"/>
								<bool key="IBUIOpaque">NO</bool>
								<bool key="IBUIClipsSubviews">YES</bool>
								<int key="IBUIContentMode">7</int>
								<bool key="IBUIUserInteractionEnabled">NO</bool>
								<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
								<string key="IBUIText">0</string>
								<reference key="IBUITextColor" ref="103932968"/>
								<nil key="IBUIHighlightedColor"/>
								<int key="IBUIBaselineAdjustment">1</int>
								<float key="IBUIMinimumFontSize">10</float>
								<int key="IBUITextAlignment">2</int>
								<reference key="IBUIFontDescription" ref="439016584"/>
								<reference key="IBUIFont" ref="1051881456"/>
							</object>
							<object class="IBUILabel" id="1009723316">
								<reference key="NSNextResponder" ref="373608001"/>
								<int key="NSvFlags">292</int>
								<string key="NSFrame">{{113, 52}, {37, 21}}</string>
								<reference key="NSSuperview" ref="373608001"/>
								<reference key="NSWindow"/>
								<reference key="NSNextKeyView" ref="1420102"/>
								<bool key="IBUIOpaque">NO</bool>
								<bool key="IBUIClipsSubviews">YES</bool>
								<int key="IBUIContentMode">7</int>
								<bool key="IBUIUserInteractionEnabled">NO</bool>
								<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
								<string key="IBUIText">0</string>
								<reference key="IBUITextColor" ref="103932968"/>
								<nil key="IBUIHighlightedColor"/>
								<int key="IBUIBaselineAdjustment">1</int>
								<float key="IBUIMinimumFontSize">10</float>
								<int key="IBUITextAlignment">2</int>
								<reference key="IBUIFontDescription" ref="439016584"/>
								<reference key="IBUIFont" ref="1051881456"/>
							</object>
							<object class="IBUILabel" id="188072306">
								<reference key="NSNextResponder" ref="373608001"/>
								<int key="NSvFlags">292</int>
								<string key="NSFrame">{{0, 52}, {115, 21}}</string>
								<reference key="NSSuperview" ref="373608001"/>
								<reference key="NSWindow"/>
								<reference key="NSNextKeyView" ref="1009723316"/>
								<bool key="IBUIOpaque">NO</bool>
								<bool key="IBUIClipsSubviews">YES</bool>
								<int key="IBUIContentMode">7</int>
								<bool key="IBUIUserInteractionEnabled">NO</bool>
								<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
								<string key="IBUIText">selected index:</string>
								<object class="NSColor" key="IBUITextColor">
									<int key="NSColorSpace">1</int>
									<bytes key="NSRGB">MSAxIDEAA</bytes>
									<object class="NSColorSpace" key="NSCustomColorSpace">
										<int key="NSID">1</int>
									</object>
								</object>
								<nil key="IBUIHighlightedColor"/>
								<int key="IBUIBaselineAdjustment">1</int>
								<float key="IBUIMinimumFontSize">10</float>
								<reference key="IBUIFontDescription" ref="439016584"/>
								<reference key="IBUIFont" ref="1051881456"/>
							</object>
						</array>
						<string key="NSFrame">{{18, 20}, {285, 139}}</string>
						<reference key="NSSuperview" ref="774585933"/>
						<reference key="NSWindow"/>
						<reference key="NSNextKeyView" ref="637654008"/>
						<reference key="IBUIBackgroundColor" ref="487574684"/>
						<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
					</object>
				</array>
				<string key="NSFrame">{{0, 20}, {320, 460}}</string>
				<reference key="NSSuperview"/>
				<reference key="NSWindow"/>
				<reference key="NSNextKeyView" ref="373608001"/>
				<object class="NSColor" key="IBUIBackgroundColor">
					<int key="NSColorSpace">3</int>
					<bytes key="NSWhite">MC43NQA</bytes>
					<object class="NSColorSpace" key="NSCustomColorSpace">
						<int key="NSID">2</int>
					</object>
				</object>
				<bool key="IBUIClearsContextBeforeDrawing">NO</bool>
				<object class="IBUISimulatedStatusBarMetrics" key="IBUISimulatedStatusBarMetrics"/>
				<string key="targetRuntimeIdentifier">IBCocoaTouchFramework</string>
			</object>
		</array>
		<object class="IBObjectContainer" key="IBDocument.Objects">
			<array class="NSMutableArray" key="connectionRecords">
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchOutletConnection" key="connection">
						<string key="label">view</string>
						<reference key="source" ref="372490531"/>
						<reference key="destination" ref="774585933"/>
					</object>
					<int key="connectionID">7</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchOutletConnection" key="connection">
						<string key="label">toolbar</string>
						<reference key="source" ref="372490531"/>
						<reference key="destination" ref="581521566"/>
					</object>
					<int key="connectionID">13</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchOutletConnection" key="connection">
						<string key="label">thumbnailPickerView</string>
						<reference key="source" ref="372490531"/>
						<reference key="destination" ref="549809473"/>
					</object>
					<int key="connectionID">16</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchOutletConnection" key="connection">
						<string key="label">imageView</string>
						<reference key="source" ref="372490531"/>
						<reference key="destination" ref="667631667"/>
					</object>
					<int key="connectionID">20</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchOutletConnection" key="connection">
						<string key="label">infoLabel</string>
						<reference key="source" ref="372490531"/>
						<reference key="destination" ref="347708628"/>
					</object>
					<int key="connectionID">23</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchOutletConnection" key="connection">
						<string key="label">reloadTimeLabel</string>
						<reference key="source" ref="372490531"/>
						<reference key="destination" ref="572627251"/>
					</object>
					<int key="connectionID">38</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchOutletConnection" key="connection">
						<string key="label">numberOfItemsSlider</string>
						<reference key="source" ref="372490531"/>
						<reference key="destination" ref="262915402"/>
					</object>
					<int key="connectionID">39</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchOutletConnection" key="connection">
						<string key="label">selectedIndexSlider</string>
						<reference key="source" ref="372490531"/>
						<reference key="destination" ref="625660746"/>
					</object>
					<int key="connectionID">40</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchOutletConnection" key="connection">
						<string key="label">numberOfItemsLabel</string>
						<reference key="source" ref="372490531"/>
						<reference key="destination" ref="141709788"/>
					</object>
					<int key="connectionID">36</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchOutletConnection" key="connection">
						<string key="label">selectedIndexLabel</string>
						<reference key="source" ref="372490531"/>
						<reference key="destination" ref="1009723316"/>
					</object>
					<int key="connectionID">37</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchOutletConnection" key="connection">
						<string key="label">controlsView</string>
						<reference key="source" ref="774585933"/>
						<reference key="destination" ref="373608001"/>
					</object>
					<int key="connectionID">57</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchOutletConnection" key="connection">
						<string key="label">imageView</string>
						<reference key="source" ref="774585933"/>
						<reference key="destination" ref="667631667"/>
					</object>
					<int key="connectionID">58</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchOutletConnection" key="connection">
						<string key="label">infoLabel</string>
						<reference key="source" ref="774585933"/>
						<reference key="destination" ref="347708628"/>
					</object>
					<int key="connectionID">59</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchOutletConnection" key="connection">
						<string key="label">delegate</string>
						<reference key="source" ref="549809473"/>
						<reference key="destination" ref="372490531"/>
					</object>
					<int key="connectionID">17</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchOutletConnection" key="connection">
						<string key="label">dataSource</string>
						<reference key="source" ref="549809473"/>
						<reference key="destination" ref="372490531"/>
					</object>
					<int key="connectionID">18</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchEventConnection" key="connection">
						<string key="label">_reloadThumbnailPickerView</string>
						<reference key="source" ref="1420102"/>
						<reference key="destination" ref="372490531"/>
						<int key="IBEventType">7</int>
					</object>
					<int key="connectionID">43</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchEventConnection" key="connection">
						<string key="label">_sliderValueChanged:</string>
						<reference key="source" ref="262915402"/>
						<reference key="destination" ref="372490531"/>
						<int key="IBEventType">13</int>
					</object>
					<int key="connectionID">41</int>
				</object>
				<object class="IBConnectionRecord">
					<object class="IBCocoaTouchEventConnection" key="connection">
						<string key="label">_sliderValueChanged:</string>
						<reference key="source" ref="625660746"/>
						<reference key="destination" ref="372490531"/>
						<int key="IBEventType">13</int>
					</object>
					<int key="connectionID">42</int>
				</object>
			</array>
			<object class="IBMutableOrderedSet" key="objectRecords">
				<array key="orderedObjects">
					<object class="IBObjectRecord">
						<int key="objectID">0</int>
						<array key="object" id="0"/>
						<reference key="children" ref="1000"/>
						<nil key="parent"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">-1</int>
						<reference key="object" ref="372490531"/>
						<reference key="parent" ref="0"/>
						<string key="objectName">File's Owner</string>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">-2</int>
						<reference key="object" ref="843779117"/>
						<reference key="parent" ref="0"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">6</int>
						<reference key="object" ref="774585933"/>
						<array class="NSMutableArray" key="children">
							<reference ref="581521566"/>
							<reference ref="667631667"/>
							<reference ref="347708628"/>
							<reference ref="373608001"/>
						</array>
						<reference key="parent" ref="0"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">8</int>
						<reference key="object" ref="581521566"/>
						<array class="NSMutableArray" key="children">
							<reference ref="13771401"/>
						</array>
						<reference key="parent" ref="774585933"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">15</int>
						<reference key="object" ref="13771401"/>
						<array class="NSMutableArray" key="children">
							<reference ref="549809473"/>
						</array>
						<reference key="parent" ref="581521566"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">14</int>
						<reference key="object" ref="549809473"/>
						<reference key="parent" ref="13771401"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">19</int>
						<reference key="object" ref="667631667"/>
						<reference key="parent" ref="774585933"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">31</int>
						<reference key="object" ref="373608001"/>
						<array class="NSMutableArray" key="children">
							<reference ref="188072306"/>
							<reference ref="637654008"/>
							<reference ref="625660746"/>
							<reference ref="262915402"/>
							<reference ref="1420102"/>
							<reference ref="572627251"/>
							<reference ref="141709788"/>
							<reference ref="1009723316"/>
						</array>
						<reference key="parent" ref="774585933"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">24</int>
						<reference key="object" ref="1420102"/>
						<reference key="parent" ref="373608001"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">30</int>
						<reference key="object" ref="572627251"/>
						<reference key="parent" ref="373608001"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">21</int>
						<reference key="object" ref="347708628"/>
						<reference key="parent" ref="774585933"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">27</int>
						<reference key="object" ref="262915402"/>
						<reference key="parent" ref="373608001"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">32</int>
						<reference key="object" ref="625660746"/>
						<reference key="parent" ref="373608001"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">28</int>
						<reference key="object" ref="637654008"/>
						<reference key="parent" ref="373608001"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">29</int>
						<reference key="object" ref="141709788"/>
						<reference key="parent" ref="373608001"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">34</int>
						<reference key="object" ref="1009723316"/>
						<reference key="parent" ref="373608001"/>
					</object>
					<object class="IBObjectRecord">
						<int key="objectID">33</int>
						<reference key="object" ref="188072306"/>
						<reference key="parent" ref="373608001"/>
					</object>
				</array>
			</object>
			<dictionary class="NSMutableDictionary" key="flattenedProperties">
				<string key="-1.CustomClassName">ViewController</string>
				<string key="-1.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="-2.CustomClassName">UIResponder</string>
				<string key="-2.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="14.CustomClassName">ThumbnailPickerView</string>
				<string key="14.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="15.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="19.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="21.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="24.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="27.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="28.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="29.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="30.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="31.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="32.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="33.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="34.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="6.CustomClassName">View</string>
				<string key="6.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
				<string key="8.IBPluginDependency">com.apple.InterfaceBuilder.IBCocoaTouchPlugin</string>
			</dictionary>
			<dictionary class="NSMutableDictionary" key="unlocalizedProperties"/>
			<nil key="activeLocalization"/>
			<dictionary class="NSMutableDictionary" key="localizations"/>
			<nil key="sourceID"/>
			<int key="maxID">59</int>
		</object>
		<object class="IBClassDescriber" key="IBDocument.Classes">
			<array class="NSMutableArray" key="referencedPartialClassDescriptions">
				<object class="IBPartialClassDescription">
					<string key="className">ThumbnailPickerView</string>
					<string key="superclassName">UIControl</string>
					<dictionary class="NSMutableDictionary" key="outlets">
						<string key="dataSource">id</string>
						<string key="delegate">id</string>
					</dictionary>
					<dictionary class="NSMutableDictionary" key="toOneOutletInfosByName">
						<object class="IBToOneOutletInfo" key="dataSource">
							<string key="name">dataSource</string>
							<string key="candidateClassName">id</string>
						</object>
						<object class="IBToOneOutletInfo" key="delegate">
							<string key="name">delegate</string>
							<string key="candidateClassName">id</string>
						</object>
					</dictionary>
					<object class="IBClassDescriptionSource" key="sourceIdentifier">
						<string key="majorKey">IBProjectSource</string>
						<string key="minorKey">./Classes/ThumbnailPickerView.h</string>
					</object>
				</object>
				<object class="IBPartialClassDescription">
					<string key="className">View</string>
					<string key="superclassName">UIView</string>
					<dictionary class="NSMutableDictionary" key="outlets">
						<string key="controlsView">UIView</string>
						<string key="imageView">UIView</string>
						<string key="infoLabel">UIView</string>
					</dictionary>
					<dictionary class="NSMutableDictionary" key="toOneOutletInfosByName">
						<object class="IBToOneOutletInfo" key="controlsView">
							<string key="name">controlsView</string>
							<string key="candidateClassName">UIView</string>
						</object>
						<object class="IBToOneOutletInfo" key="imageView">
							<string key="name">imageView</string>
							<string key="candidateClassName">UIView</string>
						</object>
						<object class="IBToOneOutletInfo" key="infoLabel">
							<string key="name">infoLabel</string>
							<string key="candidateClassName">UIView</string>
						</object>
					</dictionary>
					<object class="IBClassDescriptionSource" key="sourceIdentifier">
						<string key="majorKey">IBProjectSource</string>
						<string key="minorKey">./Classes/View.h</string>
					</object>
				</object>
				<object class="IBPartialClassDescription">
					<string key="className">ViewController</string>
					<string key="superclassName">UIViewController</string>
					<dictionary class="NSMutableDictionary" key="actions">
						<string key="_reloadThumbnailPickerView">id</string>
						<string key="_sliderValueChanged:">UISlider</string>
					</dictionary>
					<dictionary class="NSMutableDictionary" key="actionInfosByName">
						<object class="IBActionInfo" key="_reloadThumbnailPickerView">
							<string key="name">_reloadThumbnailPickerView</string>
							<string key="candidateClassName">id</string>
						</object>
						<object class="IBActionInfo" key="_sliderValueChanged:">
							<string key="name">_sliderValueChanged:</string>
							<string key="candidateClassName">UISlider</string>
						</object>
					</dictionary>
					<dictionary class="NSMutableDictionary" key="outlets">
						<string key="imageView">UIImageView</string>
						<string key="infoLabel">UILabel</string>
						<string key="numberOfItemsLabel">UILabel</string>
						<string key="numberOfItemsSlider">UISlider</string>
						<string key="reloadTimeLabel">UILabel</string>
						<string key="selectedIndexLabel">UILabel</string>
						<string key="selectedIndexSlider">UISlider</string>
						<string key="thumbnailPickerView">ThumbnailPickerView</string>
						<string key="toolbar">UIToolbar</string>
					</dictionary>
					<dictionary class="NSMutableDictionary" key="toOneOutletInfosByName">
						<object class="IBToOneOutletInfo" key="imageView">
							<string key="name">imageView</string>
							<string key="candidateClassName">UIImageView</string>
						</object>
						<object class="IBToOneOutletInfo" key="infoLabel">
							<string key="name">infoLabel</string>
							<string key="candidateClassName">UILabel</string>
						</object>
						<object class="IBToOneOutletInfo" key="numberOfItemsLabel">
							<string key="name">numberOfItemsLabel</string>
							<string key="candidateClassName">UILabel</string>
						</object>
						<object class="IBToOneOutletInfo" key="numberOfItemsSlider">
							<string key="name">numberOfItemsSlider</string>
							<string key="candidateClassName">UISlider</string>
						</object>
						<object class="IBToOneOutletInfo" key="reloadTimeLabel">
							<string key="name">reloadTimeLabel</string>
							<string key="candidateClassName">UILabel</string>
						</object>
						<object class="IBToOneOutletInfo" key="selectedIndexLabel">
							<string key="name">selectedIndexLabel</string>
							<string key="candidateClassName">UILabel</string>
						</object>
						<object class="IBToOneOutletInfo" key="selectedIndexSlider">
							<string key="name">selectedIndexSlider</string>
							<string key="candidateClassName">UISlider</string>
						</object>
						<object class="IBToOneOutletInfo" key="thumbnailPickerView">
							<string key="name">thumbnailPickerView</string>
							<string key="candidateClassName">ThumbnailPickerView</string>
						</object>
						<object class="IBToOneOutletInfo" key="toolbar">
							<string key="name">toolbar</string>
							<string key="candidateClassName">UIToolbar</string>
						</object>
					</dictionary>
					<object class="IBClassDescriptionSource" key="sourceIdentifier">
						<string key="majorKey">IBProjectSource</string>
						<string key="minorKey">./Classes/ViewController.h</string>
					</object>
				</object>
			</array>
		</object>
		<int key="IBDocument.localizationMode">0</int>
		<string key="IBDocument.TargetRuntimeIdentifier">IBCocoaTouchFramework</string>
		<bool key="IBDocument.PluginDeclaredDependenciesTrackSystemTargetVersion">YES</bool>
		<int key="IBDocument.defaultPropertyAccessControl">3</int>
		<string key="IBCocoaTouchPluginVersion">933</string>
	</data>
</archive>
