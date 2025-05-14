# @/components/Layout

![MIT license](https://badgen.now.sh/badge/license/MIT)

[Source](https://github.com/jtsamzg/fullstack-nextjs-app/tree/main/src/components/Layout)


## Examples

```js
import React from 'react';
import Layout from '@/components/Layout';


const MainContent = () => {
    return (
        <>
            <p>
                Text here...
            </p>

        </>
    )

};

export default () => {
  return (
    <>
        <Layout
            isHome={true}
            ssrNav={[...]}
            pageTitle="Page Title Here"
            contentComponent={<><MainContent /></>}
        />


        <Layout
            pageTitle="Page Title Here"
            contentComponent={<><MainContent /></>}
        />
    </>
  );
}

```