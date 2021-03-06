## API Report File for "@backstage/plugin-explore"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

/// <reference types="react" />

import { BackstagePlugin } from '@backstage/core-plugin-api';
import { default } from 'react';
import { ExternalRouteRef } from '@backstage/core-plugin-api';
import { RouteRef } from '@backstage/core-plugin-api';
import { TabProps } from '@material-ui/core';

// @public (undocumented)
export const catalogEntityRouteRef: ExternalRouteRef<    {
name: string;
kind: string;
namespace: string;
}, false>;

// @public (undocumented)
export const DomainExplorerContent: ({ title, }: {
    title?: string | undefined;
}) => JSX.Element;

// @public
export const ExploreLayout: {
    ({ title, subtitle, children, }: ExploreLayoutProps): JSX.Element;
    Route: (props: SubRoute) => null;
};

// @public (undocumented)
export const ExplorePage: () => JSX.Element;

// @public (undocumented)
const explorePlugin: BackstagePlugin<    {
explore: RouteRef<undefined>;
}, {
catalogEntity: ExternalRouteRef<    {
name: string;
kind: string;
namespace: string;
}, false>;
}>;
export { explorePlugin }
export { explorePlugin as plugin }

// @public (undocumented)
export const exploreRouteRef: RouteRef<undefined>;

// @public (undocumented)
export const GroupsExplorerContent: ({ title, }: {
    title?: string | undefined;
}) => JSX.Element;

// @public (undocumented)
export const ToolExplorerContent: ({ title }: {
    title?: string | undefined;
}) => JSX.Element;

// (No @packageDocumentation comment for this package)

```
