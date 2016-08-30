workspace(name = "tf_serving")

local_repository(
    name = "org_tensorflow",
    path = "tensorflow",
)

# Please add all new TensorFlow Serving dependencies in workspace.bzl.
load('//tensorflow_serving:workspace.bzl', 'tf_serving_workspace')
tf_serving_workspace()
