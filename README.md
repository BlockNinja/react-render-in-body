# Render In Body

Simple React Component to render components under the body tag. Useful for dropdown menus, modals, load masking etc.

## Installation

`npm install --save react-render-in-body`

## Usage

```jsx
import RenderInBody from 'react-render-in-body'

class Prompt extends Component{
	render() {
		return (
			<RenderInBody>
					<div className="prompt">
						{this.props.text}<br/>
						<input type="text" ref="input" />
						<footer>
							<button onClick={this.props.OK}>OK</button>
							<button onClick={this.props.Cancel}>Cancel</button>
						</footer>
					</div>
				</div>
			</RenderInBody>
		)
	}
}
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

Forked from James K Nelson's good work: https://github.com/unicorn-standard/react-render-in-body

Forked so it could be published to NPM & maintained.

## Credits

Credit goes to James K Nelson

## License

TODO: MIT
