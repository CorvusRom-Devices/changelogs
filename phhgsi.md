# GSI
<!-- Table format
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM32</th>
		<td>
			<table>
                		<tr>
					<th>Non-Gapps</th>
					<td></td>
                		</tr>
                		<tr>
					<th>Gapps</th>
					<td></td>
                		</tr>
        		</table>
		</td>
		<td>
			<table>
                		<tr>
					<th>Non-Gapps</th>
					<td></td>
                		</tr>
                		<tr>
					<th>Gapps</th>
					<td></td>
                		</tr>
        		</table>
		</td>
	</tr>
	<tr>
		<th>ARM32_binder64</th>
		<td>N/A</td>
		<td>
        		<table>
                		<tr>
					<th>VNDK Lite</th>
					<td>
						<table>
                					<tr>
								<th>Non-Gapps</th>
								<td></td>
                					</tr>
                					<tr>
								<th>Gapps</th>
								<td></td>
                					</tr>
        					</table>
					</td>
                		</tr>
                		<tr>
					<th>VNDK Non-Lite</th>
					<td>
						<table>
                					<tr>
								<th>Non-Gapps</th>
								<td></td>
                					</tr>
                					<tr>
								<th>Gapps</th>
								<td></td>
                					</tr>
        					</table>
					</td>
                		</tr>
        		</table>
        	</td>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>
			<table>
                		<tr>
					<th>Non-Gapps</th>
					<td></td>
                		</tr>
                		<tr>
					<th>Gapps</th>
					<td></td>
                		</tr>
        		</table>
		</td>
		<td>
			<table>
  				<tr>
					<th>VNDK Lite</th>
					<td>
						<table>
                					<tr>
								<th>Non-Gapps</th>
								<td></td>
                					</tr>
                					<tr>
								<th>Gapps</th>
								<td></td>
                					</tr>
        					</table>
					</td>
                		</tr>
                		<tr>
					<th>VNDK Non-Lite</th>
					<td>
						<table>
                					<tr>
								<th>Non-Gapps</th>
								<td></td>
                					</tr>
                					<tr>
								<th>Gapps</th>
								<td></td>
                					</tr>
        					</table>
					</td>
				</tr>
        		</table>
        	</td>
	</tr>
</table>
-->

<!--
	Emojis
		✓ - Tick
		✕ - Cross
-->

## CorvusOS vS3.2 Vindicate
### 2022-07-09 (Official)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✕</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✓</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>

- CorvusOS vS3.2 Vindicate
- Frameworks SPL: July 2022
- Google Apps SPL: June 2022
- PHH patches: v414
- Introduing: Slim Gapps variant
- Switch to using prop modifications for FOD color
- Now allows user to change the FPS Info QS Tile's sys node path
- Now shows you the device info correctly in CorvusOS device info panel
- Now includes Camera2 by default

## CorvusOS vS3.0 Revenant
### 2022-06-03 (Beta-Official)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✕</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✓</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>

- Updated patches to Phh v413
- Updated to CorvusOS vS3.0
- Enabled FOD icons and animations

## CorvusOS vS2.1 Revolt
### 2022-04-23 (Beta-Official)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✕</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✓</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>

- Drop more secure variant, now automatically copies model information
- Remove phh-su
- Fixed UDFPS with custom UdfpsExtension
- Add Vendor Security Update information to About phone
- Various patches from eremitein
- Meizu 18 vibration patches from Andy Yan
- Added OTA support

### 2022-04-20 (Beta-Official)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✕</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✓</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>

- Updated patches to Phh v412
- Updated to CorvusOS vS2.1
- Enabled FOD icons and animations
- Enabled Raven features
- Now obtains Bluetooth name from your device
- New SPen Pointer overlay

## CorvusOS v16.8 Avalon
### 2021-08-25 (Beta-Official)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✕</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✓</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>

- Welcome to CorvusOS v16.8 Avalon!
- Update to PHH to r40
- Includes Magisk /sbin fix

## CorvusOS v16.7 Obsidian
### 2021-08-05 (Beta-Official)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✕</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✓</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>

- Welcome to CorvusOS 16.7 Obsidian!
- PHH Treble patchset has been updated to v310 (r39)
- Now using our own FOD implementation instead of PHH's

## CorvusOS v16.6 Paradox
### 2021-07-08 (Beta-Official)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✕</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✓</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>

- Update to CorvusOS v16.6 Paradox
- Add AndyCGYan's patches

## CorvusOS v16.5 Alpha-Centauri
### 2021-06-23 (Beta)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM32</th>
		<td>
			<table>
                		<tr>
					<th>Non-Gapps</th>
					<td>✓</td>
                		</tr>
                		<tr>
					<th>Gapps</th>
					<td>✓</td>
                		</tr>
        		</table>
		</td>
		<td>
			<table>
                		<tr>
					<th>Non-Gapps</th>
					<td>✓</td>
                		</tr>
                		<tr>
					<th>Gapps</th>
					<td>✓</td>
                		</tr>
        		</table>
		</td>
	</tr>
	<tr>
		<th>ARM32_binder64</th>
		<td>N/A</td>
		<td>
        		<table>
                		<tr>
					<th>VNDK Lite</th>
					<td>
						<table>
                					<tr>
								<th>Non-Gapps</th>
								<td>✓</td>
                					</tr>
                					<tr>
								<th>Gapps</th>
								<td>✓</td>
                					</tr>
        					</table>
					</td>
                		</tr>
                		<tr>
					<th>VNDK Non-Lite</th>
					<td>
						<table>
                					<tr>
								<th>Non-Gapps</th>
								<td>✓</td>
                					</tr>
                					<tr>
								<th>Gapps</th>
								<td>✓</td>
                					</tr>
        					</table>
					</td>
                		</tr>
        		</table>
        	</td>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>
			<table>
                		<tr>
					<th>Non-Gapps</th>
					<td>✓</td>
                		</tr>
                		<tr>
					<th>Gapps</th>
					<td>✓</td>
                		</tr>
        		</table>
		</td>
		<td>
			<table>
  				<tr>
					<th>VNDK Lite</th>
					<td>
						<table>
                					<tr>
								<th>Non-Gapps</th>
								<td>✓</td>
                					</tr>
                					<tr>
								<th>Gapps</th>
								<td>✓</td>
                					</tr>
        					</table>
					</td>
                		</tr>
                		<tr>
					<th>VNDK Non-Lite</th>
					<td>
						<table>
                					<tr>
								<th>Non-Gapps</th>
								<td>✓</td>
                					</tr>
                					<tr>
								<th>Gapps</th>
								<td>✓</td>
                					</tr>
        					</table>
					</td>
				</tr>
        		</table>
        	</td>
	</tr>
</table>

- Bump to v16.5
- Update to phh patches r38

## CorvusOS v16.0 Alpha-Centauri
### 2021-05-10 (Pre-Beta)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✕</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✕</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>

- Bump to v16.0
- Update to phh patches r37

## CorvusOS v15.0 RavenClaw
### 2021-03-29 (Alpha)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✓</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✓</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>

- source: Bump to CorvusOS v15.0 RavenClaw
- device/phh/treble: Merged phh device tree
- vendor/corvus-gsi: Update to phh r32 patches
- vendor/corvus-gsi: Slight rework of patches, inline with other patchsets
- vendor/generify: Use latest dev branch changes


## CorvusOS v14.0 Ruinous
### 2021-02-14 (Alpha)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✕</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✕</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>

- source: Bump to CorvusOS v14.0 Ruinous
- device/phh/treble: Rework whole device tree
- vendor/corvus-gsi: Rework patches, inline with other patchsets
- vendor/generify: Use latest dev branch changes
- device/generic/common: Use GSI NFC conf

## CorvusOS v13.0 Exalted
### 2021-01-17 (Alpha)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✓</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✓</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>

- Stop building fuseblk sepolicy by default

### 2021-01-16 (Alpha)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✕</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✕</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>

- Initial CorvusOS v13.0 Exalted build
- Updated to phh r28 patches

## CorvusOS v12.5-XMAS
### 2021-01-01 (Alpha)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✕</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✕</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>


### 2020-12-31 (Alpha)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✓</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✓</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>

- Finally Alpha!
- Updated to latest phh patches
- Included vndk-test-sepolicy
- New build types!

### 2020-12-28 (Pre-Alpha)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✕</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✕</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>

- Updated to v12.5 XMAS source

## CorvusOS v11.0 Spooky
### 2020-12-23 (Pre-Alpha)
<table>
	<tr>
		<th>Architecture / Type</th>
		<th>A Only</th>
		<th>A/B</th>
	</tr>
	<tr>
		<th>ARM64</th>
		<td>✕</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td>✕</td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td>✓</td>
                </tr>
        	</table>
        </td>
	</tr>
</table>

- Initial build
