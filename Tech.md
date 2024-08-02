---


---

<h1 id="technical-document-for-universal-react-widgets-implementation">Technical Document for Universal React Widgets Implementation</h1>
<h2 id="overview">Overview</h2>
<p>The transition to universal React widgets as web components aims to address several challenges associated with the current Angular-based implementation. The primary goals are to streamline the development process, enhance performance, and simplify maintenance and theming. The universal widgets approach will leverage React’s strengths, modular design, and npm packages to create a more efficient and scalable solution.</p>
<h3 id="challenges-with-current-angular-implementation">Challenges with Current Angular Implementation</h3>
<p>Unorganized SCSS for Theming:</p>
<ul>
<li>
<p>Modifying poorly organized SCSS for theming is time-consuming and error-prone.</p>
</li>
<li>
<p>Removing unnecessary modules adds to the complexity.</p>
</li>
</ul>
<p>Unit Testing and UI Automation:</p>
<ul>
<li>Increased workload due to the need for unit tests and UI automation across multiple apps.</li>
</ul>
<p>Feature Implementation:</p>
<ul>
<li>Adding new features requires changes in every client’s web app.</li>
</ul>
<p>Performance Issues:</p>
<ul>
<li>The current Angular app performs slower compared to React.</li>
</ul>
<h3 id="solution-universal-react-widgets-as-web-components">Solution: Universal React Widgets as Web Components</h3>
<p><strong>Benefits:</strong></p>
<p>Modular and Reusable Components:</p>
<ul>
<li>
<p>Standalone npm packages allow for code reuse across multiple projects.</p>
</li>
<li>
<p>Ensures consistency and reduces the need to rewrite code.</p>
</li>
</ul>
<p>Improved Performance:</p>
<ul>
<li>React’s performance advantages lead to faster and more efficient client websites.</li>
</ul>
<p>Easier Maintenance and Updates:</p>
<ul>
<li>
<p>Independent npm packages simplify updates and feature additions.</p>
</li>
<li>
<p>Changes propagate to all client projects with minimal effort.</p>
</li>
</ul>
<p>Theming and Customization:</p>
<ul>
<li>
<p>SCSS designed for easy theming and customization.</p>
</li>
<li>
<p>Adapt to different client needs without significant rework.</p>
</li>
</ul>
<p>Reduced Complexity:</p>
<ul>
<li>
<p>Import only necessary widgets to minimize bloat.</p>
</li>
<li>
<p>Simplifies the initial setup process for new clients.</p>
</li>
</ul>
<p>Automated Testing:</p>
<ul>
<li>
<p>Isolated widgets make unit testing and UI automation more manageable.</p>
</li>
<li>
<p>Focused testing leads to more reliable applications.</p>
</li>
</ul>

