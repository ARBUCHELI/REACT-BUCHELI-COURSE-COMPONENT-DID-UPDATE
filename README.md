# REACT-BUCHELI-COURSE-COMPONENT-DID-UPDATE

# REACT-LESSONS-INSTRUCTOR-ANDRES-R.-BUCHELI

## Usage:

Remember the three parts of a component’s lifecycle:

* Mounting, when the component is being initialized and put into the DOM for the first time
* Updating, when the component updates as a result of changed state or changed props
* Unmounting, when the component is being removed from the DOM

We’ve looked at mounting (constructor(), render(), and componentDidMount()). We’ve looked at unmounting (componentWillUnmount()). Let’s finish by looking at the updating phase.

An update is caused by changes to props or state. You’ve already seen this happen a bunch of times. Every time you’ve called setState() with new data, you’ve triggered an update. Every time you change the props passed to a component, you’ve caused it to update.

When a component updates, it calls several methods, but only two are commonly used.

The first is render(), which we’ve seen in every React component. When a component’s props or state changes, render() is called.

The second, which we haven’t seen yet, is componentDidUpdate(). Just like componentDidMount() is a good place for mount-phase setup, componentDidUpdate() is a good place for update-phase work.
