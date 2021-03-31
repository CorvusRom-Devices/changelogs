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
		<td></td>
		<td></td>
	</tr>
    <tr>
		<th>ARM32_binder64</th>
		<td>N/A</td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td></td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td></td>
                </tr>
        	</table>
        </td>
	</tr>
	<tr>
		<th>ARM64</th>
		<td></td>
		<td>
        	<table>
                <tr>
                	<th>VNDK Lite</th>
                    <td></td>
                </tr>
                <tr>
                	<th>VNDK Non-Lite</th>
                    <td></td>
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
