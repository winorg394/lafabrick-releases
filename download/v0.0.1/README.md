# Version Control Documentation

## Version Structure
Our versioning follows the Semantic Versioning (SemVer) pattern: `v{MAJOR}.{MINOR}.{PATCH}`

Example: `v0.0.1`

- **MAJOR**: Breaking changes or significant feature updates
- **MINOR**: New features with backward compatibility
- **PATCH**: Bug fixes and minor improvements

## Release Directory Structure

## Version History

### v0.0.1 (Initial Release)
- Basic functionality implementation
- Core features setup
- Initial system architecture

## How to Access Versions
1. Navigate to the `releases/download` directory
2. Select the desired version folder (e.g., `v0.0.1`)
3. Download or view the files for that specific version

## Version Update Process
1. Changes are made in the development environment
2. Version number is incremented based on change type
3. New version folder is created in `releases/download`
4. Updated files are placed in the new version folder

## Notes
- Each version maintains its own separate directory
- Previous versions remain accessible for reference
- Documentation is updated with each new release


git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/winorg394/lafabrick-releases.git
git push -u origin main