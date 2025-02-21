# @mostly-it/simple-actors

A simple Actor Model implementation written in TypeScript for the web.

## Solutions

### Source Code

The library is written in **TypeScript** and uses the _TypeScript compiler_ to check the code during development.

<table>
  <tr>
    <th>Configuration file</th>
    <th>Configuration description</th>
  </tr>
  <tr>
    <td>package.json</td>
    <td><ul>
      <li>The TypeScript compiler is run without outputs for type checking during testing script.</li>
      <li>TypeScript is added as a development dependency for code checking during development.</li>
      <li>TypeScript is added as a peer dependency because it is required by consumers of this package.</li>
    </ul></td>
  </tr>
  <tr>
    <td>tsconfig.json</td>
    <td><ul>
      <li>TypeScript is configured to check files and not emit JavaScript.</li>
    </ul></td>
  </tr>
</table>

### Persistent Collections

**ImmutableJS** is used for its persistent collections.

### Testing

**Vitest** is used for testing purposes.

<table>
  <tr>
    <th>Configuration file</th>
    <th>Configuration description</th>
  </tr>
  <tr>
    <td>vitest.config.ts</td>
    <td><ul>
      <li>Basic configuration.</li>
    </ul></td>
  </tr>
</table>

### Package Distribution

**npm** is used as package distribution solution.

<table>
  <tr>
    <th>Configuration file</th>
    <th>Configuration description</th>
  </tr>
  <tr>
    <td>package.json</td>
    <td><ul>
      <li>Various pieces of package metadata, such as homepage and license, is filled out.</li>
    </ul></td>
  </tr>
</table>
