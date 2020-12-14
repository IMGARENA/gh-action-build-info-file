# gh-action-build-info-file

This Action creates a build artefact file with info on the build.

## Inputs

### `output-location`

The path where the file should be created, defaults to `dist`.

### `artefact-filename`

The filename for the artefact, defaults to `_i` which will end up being `dist/_i.json`.

## Outputs

This action doesn't provide any GH Actions output, but adds a file to the build.

## Example usage

    - name: Create a build info file
      id: build-info
      uses: IMGARENA/gh-action-build-info-file@v1
