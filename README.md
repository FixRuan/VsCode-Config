Snippet

{
	"Basic React Native Interface": {
		"prefix": "rnfc",
		"body": [
			"import React from 'react';",
			"",
			"import {",
			"   Container",
			"} from './styles.ts';",
			"",
			"export function ${TM_DIRECTORY/^.+[\\/\\\\]+(.*)$/$1/}(){",
			"   return(",
			"     <Container>",
			"",
			"     </Container>",
			"   );",
			"}"
		],
		"description": "Basic React Native Interface With Styled Component"
	},
	"Basci Styled Components Interfacec":{
		"prefix": "sty",
		"body": [
			"import styled from 'styled-components/native'",
			"",
			"export const Container = styled.View`",
			"   flex: 1;",
			"`;",
		],
		"description": "Basic Styled Components Interface"
	}
}
